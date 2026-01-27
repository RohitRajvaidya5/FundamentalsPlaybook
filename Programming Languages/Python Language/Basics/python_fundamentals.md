
# Python Fundamentals
---

## What is Python (features, use cases)


Python is a [dynamically typed](../Glossary/glossary.md#dynamically-typed),open source, high level and general purpose language which support both object-oriented and procedural-oriented programming.


## Python execution model (source → bytecode → PVM)

**Basic Mental Model** :

> ---
> 
> ##### Python Code &rarr; Bytecode &rarr; Low Level CPU architecture instructions
> 
> ---


so if i create code like this 

```python
print("Hello World")
```

After run it in terminal like `python script.py` it will first convert whole code into bytecode. Bytecode is generated in memory and may be cached in `__pycache__` as a .pyc file. That bytecode will be executed with the help of PVM ( Python Virtual Machine ).

```

Python source (.py)
→ compiled to bytecode (.pyc or in-memory)
→ executed by Python Virtual Machine (PVM)
→ CPU executes the PVM’s native instructions

```

---

## Interpreted Vs Compiled

Python uses a bytecode compilation model rather than direct native compilation, trading runtime speed for portability and developer productivity.


 


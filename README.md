# Hello nbdev
> This project is for learning and trying nbdev.


This file will become your README and also the index of your documentation.

## Install

If I would release it, this project could be available via:
`pip install hello_nbdev`

## How to use

This library doesn't do much.


```python
import hello_nbdev as nb
```

```python
nb.core
```




    <module 'hello_nbdev.core' from '/storage/hello_nbdev/hello_nbdev/core.py'>



```python
dir(nb.core)
```




    ['HelloSayer',
     '__all__',
     '__builtins__',
     '__cached__',
     '__doc__',
     '__file__',
     '__loader__',
     '__name__',
     '__package__',
     '__spec__',
     'hello']



```python
nb.core.hello("index")
```




    'hello index! this is nbdev !!'



```python
nb.core.hello?
```

### Note
> When importing a module from another notebook, make sure that you did not import an older version before. Restart the kernel and import everything again, then the changes in the module will be visible. Do not forget to build the library as well with nb_build_lib.

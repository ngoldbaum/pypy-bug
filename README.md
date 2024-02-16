Build with:

```
python setup.py build_ext --inplace
```

And then run:

```
python -c "import test_cython"
```

If there is no bug, it should print True.

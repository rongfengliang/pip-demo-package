# pip-demo-package

pip-demo-package

## example_pkg deploy

* into example_pkg directory

```code
cd example_pkg
```

* install setuptools

```code
python3 -m pip install --user --upgrade setuptools wheel

```

* generating distribution archives

```code
python3 setup.py sdist bdist_wheel
```

* install upload tools

```code
python3 -m pip install --user --upgrade twine
```

* create account  for test pypi

```code
https://test.pypi.org/account/register/
```

* upload archives

```code
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
```

## useage

```code
cd useage
python app.py
```
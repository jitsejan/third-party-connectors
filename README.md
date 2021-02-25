

# Getting started

```bash
❯ pyenv install 3.9.0
❯ pyenv virtualenv 3.9.0 third-party-connectors-env
❯ pyenv activate third-party-connectors-env
```


```
❯ pip install -e .
Obtaining file:///Users/jitse-jan.vanwaterschoot/code/third-party-connectors/connectors
Installing collected packages: connectors
  Running setup.py develop for connectors
Successfully installed connectors

❯ pip freeze
# Editable Git install with no remote (connectors==0.1)
-e /Users/jitse-jan.vanwaterschoot/code/third-party-connectors/connectors
```

And after setting up Git

```
❯ pip freeze
-e git+https://github.com/jitsejan/third-party-connectors.git@668058edb20f206df647f74bc725fc4c3775813c#egg=connectors&subdirectory=connectors
```

# Pipenv

## Install
```bash
# Install pipenv
pip3 install pipenv

# Install python module
pipenv install <Module>
pipenv install -r requirement.txt

# Uninstall python module
pipenv uninstall <Module>
pipenv uninstall -r requirement.txt
```

## Virtual Enviroment
```bash
# Generate python virtual enviroment
pipenv --python <Version>

# Execute a single program (without entering the virtual environment)
pipenv run python <Filename>

# Enter the virtual enviroment
pipenv shell
```

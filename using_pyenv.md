# Создание виртуальных окружений с необходимыми версиями Python
### Устанавливаем pyenv
[pyenv installation](https://github.com/pyenv/pyenv#installation)
### Устанавливаем необходимую версию Python и активируем
```commandline
pyenv install <version>
pyenv global <version> <version2> <...>
```
### Просмотр доступных версий и активированной версии
```commandline
pyenv versions
pyenv global
```
### Активация pyenv в текущей консоли
```commandline
eval "$(pyenv init --path)"
```
### Создание виртуального окружения
```commandline
python -m venv <env_name>
pip install <package> --trusted-host pypi.python.org --trusted-host files.pythonhosted.org --trusted-host pypi.org
```

# Создание виртуальных окружений с необходимыми версиями Python
### Устанавливаем pyenv
```commandline
sudo apt-get install git python-pip make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev curl
git clone https://github.com/yyuu/pyenv.git ~/.pyenv
```
или
```commandline
brew update
brew install pyenv
```
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
eval "$(pyenv init -)"
```
### Создание виртуального окружения
```commandline
python -m venv <env_name>
```

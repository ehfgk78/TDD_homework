# 설치 환경 

git init

vi .gitignore

pyenv virtualenv 3.6.2 tdd00

pyenv local tdd00

pip install django, django-extensions, ipython, selenium

pip freeze > requirements.txt



### Firefox driver 설치 

```sh
$ wget https://github.com/mozilla/geckodriver/releases/download/v0.19.0/geckodriver-v0.19.0-linux64.tar.gz
$ tar -xvzf geckodriver*
$ chmod +x geckodriver

$ vi .zshrc
export PATH=$PATH:/path/to/
```




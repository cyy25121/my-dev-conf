macOS工作環境設置
=================
* Preposition
  * Homebrew
  * Shell
  * iTerm2
  * Python
* Editor
  * Vim
  * Sublime
* Package / Plugin /Tool
  * Machine Learning
  * Deep Learning
  * Big Data
  * Database
  * Computer Vision
  * System
* TODO

---
* macOS High Sierra 10.13.4
* MacBook Pro, late 2013 

---

# Preposition 
## Homebrew
macOS package manager
```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
### Package
```shell
brew install wget
```

## ZSH
```shell
brew install zsh zsh-completions
chsh -s $(which zsh)
```

### oh-my-zsh
```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
* 使用theme：https://github.com/caiogondim/bullet-train.zsh

## iTerm2
* 官網下載: https://www.iterm2.com/
* 改變主題設定

## Python
以`Python 3.6`為主
```shell
brew install python3
brew install python@2
pip3 install virtualenvwrapper
```
---

# Editor
## Vim
* 用於系統內設定檔編輯，或者 **臨時** 要編輯程式碼時使用。
* 套件管理：`spf13`
```shell
curl http://j.mp/spf13-vim3 -L -o - | sh
```

---

# Package / Plugin / Tool
主要開發以`Python`和`C/C++`相關的套件以及工具為主

## Machine Learning
```shell
pip3 install numpy
pip3 install scipy
pip3 install jupyter
pip3 install jupyterlab
pip3 install sklearn
pip3 install pandas
pip3 install matplotlib
pip3 install seaborn
pip install jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
# XGBoost (optional)
brew install gcc@5
pip3 install xgboost
```

## Deep Learning (without GPU in macOS)
```
pip3 install tensorflow
pip3 install torch torchvision 
pip3 install keras
```

## Big Data
```
brew cask install caskroom/versions/java8
pip3 install awscli
pip3 install saws
```

## Database
```
brew install mongo
```

## Computer Vision
```
brew install opencv
```

## System
```
brew install htop
```

## C/C++
```
brew install gcc@6
brew install gdb
```
### gdb setting
Ref: https://stackoverflow.com/questions/18423124/please-check-gdb-is-codesigned-see-taskgated8-how-to-get-gdb-installed-w

# TODO
* R
* PySpark
* How to install opencv python package
* text editor encoding
* git encoding
* LaTex

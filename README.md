# zshrc

## <a name="usage">Usage

### zsh install
Linux
```
$ sudo apt-get install zsh
```
OS X
```
$ brew update
$ brew install zsh
```
쉘 변경 후 재시작
```
$which zsh
/usr/bin/zsh
$chsh -s /usr/bin/zsh
```
OS X 에서만 추가로 필요
```
$ echo $SHELL
/usr/bin/zsh
```
### oh-my-zsh install
```
$ curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
```

### zshrc

```sh
$ cd ~
$ git clone --recursive https://github.com/KyeongminNoh/zshrc ~/.zsh
$ ln -s .zsh/zshrc .zshrc
$ ln -s .zsh/zshenv .zshenv
```

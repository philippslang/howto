curses libs:
```
sudo apt-get install libncurses-dev
```

gnu global:
```
wget http://tamacom.com/global/global-6.4.tar.gz
tar zxvf global-6.4.tar.gz
cd global-6.4
./configure
make
sudo make install
```

emacs
```
sudo apt-get install build-essential
sudo apt-get build-dep emacs24
sudo apt-get install emacs24
```

set up init file
```
./emacs
C-x C-f ~/.emacs.d/init.el RET
```

setup melpa package manager
```
(require 'package)
(add-to-list 'package-archives'("melpa" . "http://melpa.milkbox.net/packages/") t)
C-x C-e
```

install 
```
M-x list-package

volatile-highlights
undo-tree
yasnippet
ggtags
```

```
git clone https://github.com/tuhdo/emacs-c-ide-demo.git ~/.emacs.d
```

https://tuhdo.github.io/emacs-tutor3.html#orgheadline16
http://apt.llvm.org/
https://vxlabs.com/2016/04/11/step-by-step-guide-to-c-navigation-and-completion-with-emacs-and-the-clang-based-rtags/

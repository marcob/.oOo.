# alswl's dot files #

这里是我的Linux 配置文件，有兴趣的可以参考，
我会慢慢将这个配置按个人喜好进化并加上注释。

目前的配置文件包括：

* vim
* vimperator
* xmonad
* xmobar
* xsession
* zsh
* Xmodmap

我是Python程序员，同时也code Javascript / html / css 。

可以在 [http://log4d.com/](http://log4d.com/) 这里找到我，这是我的博客。

需要帮助的话，通过 alswlx(at)gmail.com 联系我。

## Vim Usage ##

``` bash
git clone --recursive https://github.com/alswl/dotfiles.git
ln -s /your/dotfiles/.vim ~/.vim
ln -s /your/dotfiles/.vimrc ~/.vimrc
vim +BundleInstall # use vundle to install scripts
```

Tips: `Bundle 'gmarik/vundle'` won't installed by vundle.
Because it was cloned by git with `recursive` .
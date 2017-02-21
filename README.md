dotvim
======

### 使用方法
- git clone https://github.com/l5oo00/dotvim .vim
- ln -s .vim/vimrc .vimrc
- 初始化 git 子模块
```bash
cd .vim
git submodule init
git submodule update --init --recursive
```
- 安装依赖
```
brew install ag
brew install cmake
npm i -g fecs
```
- 打开vim，自动安装插件， `vi`
- 进入.vim/bundle/YouCompleteMe目录,编译 `./install.py --clang-completer`
- 进入.vim/bundle/tern-for-vim目录，执行 `git submodule update --init --recursive`
- 进入.vim/bundle/vim-jsbefautify目录，执行 `npm i`
- 进入.vim/vim_template目录,修改模板,模板config在config.vim, 详情见http://blog.csdn.net/orangleliu/article/details/41902851



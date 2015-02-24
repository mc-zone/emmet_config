# emmet_config
Collect my own configuration files for different environments of the Emmet (Vim,ST2)

自用配置。大部分参照了[yisibl/emmet-plus](https://github.com/yisibl/emmet-plus)

# Vim 分支
##使用[webabi-vim](https://github.com/mattn/webapi-vim)在 `.vimrc` 中自定义加载配置文件

例:

```viml
let g:user_emmet_settings = webapi#json#decode(join(readfile(expand('~/.vim/emmet-custom.json')), "\n"))
```

# Sublime Text2 

见`st2`分支



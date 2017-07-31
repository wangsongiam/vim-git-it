# Vim Git it!
> ##### do git add, git commit(with your message), and git push in one command

Whenever you just want to push all your recent changes with a message, just
`:Gitit {Your message}` and it's done.
### Demo
![Demo](https://cdn.rawgit.com/wangsongiam/vim-git-it/4fbe4e42/demo/git%20it.gif)

### Installation 
Use your favorite plugin manager
> eg. For vim-plug user
``` vim
Plug 'skywind3000/asyncrun.vim'
Plug 'wangsongiam/vim-git-it'
```

### Mapping
```vim
nnoremap {shortcut} :Gitit 
```
> eg. if you want to trigger it with leaderkey and p
```vim
nnoremap <leader>p :Gitit
```
and type <leader>p to start editing your commit message!, remember to hit enter
at the end


### Todos:
* Run in the background
* add non-pushing command

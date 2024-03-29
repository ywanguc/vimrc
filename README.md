# vimrc
My Vim Configuration - it is tailored for LaTex, Python, C/C++, Markdown, and Org-mode.

Note: This vimrc file is based on and modified from [Maple's Vim Config](https://github.com/humiaozuzu/dot-vimrc)


Usage
----------------

* Install this vimrc file and bundle/vundle

    ```cd```
    
    ```mkdir ~/.vim```
    
    ```curl -o ~/.vim/vimrc https://raw.githubusercontent.com/ywanguc/vimrc/master/vimrc```
    
    ```ln -s ~/.vim/vimrc ~/.vimrc```

    ```git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle```
    
* Install plugins

    ```vim``` (Note: you will get error/warning messages. No worries, just ignore)
    
    In vim, run ```:BundleInstall```
    

* Install tex.snippets (optional: for fast tex editing, modified from gillescastel/latex-snippets)

    ```mkdir ~/.vim/UltiSnips```

    ```curl -o ~/.vim/UltiSnips/tex.snippets https://raw.githubusercontent.com/ywanguc/vimrc/master/tex.snippets```
    
 
 * Complete installation for markdown preview
 
    In vim, run ```:call mkdp#util#install()```

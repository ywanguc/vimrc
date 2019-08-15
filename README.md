# vimrc
My Vim Configuration - it is tailored for LaTex, Python, C/C++ and Org-mode.

Note: This vimrc file is based on and modified from [Maple's Vim Config](https://github.com/humiaozuzu/dot-vimrc)


Usage
----------------

* Install this vimrc file and bundle/vundle

    ```cd```
    
    ```mkdir ~/.vim```
    
    ```curl -o ~/.vim/vimrc xxxx```
    
    ```ln -s ~/.vim/vimrc ~/.vimrc```

    ```git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle```
    
* Install plugins

    ```vim```
    
    In vim, run ```:BundleInstall```
    

* Install tex.snippets (optional: for fast tex editing, from gillescastel/latex-snippets)

    ```mkdir ~/.vim/UltiSnips```

    ```curl -o ~/.vim/UltiSnips/tex.snippets https://raw.githubusercontent.com/gillescastel/latex-snippets/master/tex.snippets```

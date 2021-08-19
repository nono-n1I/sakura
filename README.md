# sakura
![sakura_screen](https://user-images.githubusercontent.com/52068717/122749773-ad6fa780-d2c8-11eb-8b32-6498529adec1.png)
![sakura_screen2](https://user-images.githubusercontent.com/52068717/122750293-456d9100-d2c9-11eb-8748-3479f3c89c63.png)

# Installation
Example (Vundle):   
   
Put this in your ```.vimrc```.
```
Plugin 'is-hoku/sakura'
```
Launch vim and run ```:PluginInstall```.

# Setting
Set up True Color in ```.vimrc```   
```
set termguicolors
let &t_8f = "\<Esc>[38;2;%lu;%lu;%lum"
let &t_8b = "\<Esc>[48;2;%lu;%lu;%lum"
```

And, install Vim with a GUI (ex. GVim, MacVim...)   

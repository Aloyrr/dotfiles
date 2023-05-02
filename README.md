# dotfiles
My Starship toml file


Hello, 

This is my configured starship toml file. I will be sharing the toml file in this repo. This was configured specifically for work but you can add changes as you wish.
This is a guide to what you can add. I just wanted to save you some time, so you don't need to go through the documentation. 

https://starship.rs/config/#prompt

To install starship:

Visit this link --> https://starship.rs/guide/#%F0%9F%9A%80-installation

See Below on how to place my config into your config (macOS / Linux) 
Please note that this can work on windows as well via powershell or WSL2, however. You may need to install a package manger such as `Chocolatey`. 

HOW TO:

1. open `~/.config/starship.toml` with your prefered editor 
2. Paste my toml file in 

I did this process with neovim:

1. `nvim ~/.config/starship.toml` 
2. `i` for insert mode 
3. paste my toml 
4. `esc` to exit insert mode 
5. `:wq` to save & quit 

If you mess up during this process 

Use `:q!` to exit without saving 


What it looks like:

![image](https://user-images.githubusercontent.com/122121292/235580359-76214761-7612-404f-89fb-9b122f706645.png)


![image](https://user-images.githubusercontent.com/122121292/235580100-c20ea8a8-4488-4d93-988d-f49770fd31ff.png)



![image](https://user-images.githubusercontent.com/122121292/235579819-899c0445-5dbe-4dc7-a78f-02b091e160fa.png)

Modules included:
 
1.[docker_context]
2. [git_branch]
3. [git_status]
4. [nodejs]
5. [time]
6. [aws]
7. [python]
8. [terraform]

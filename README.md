# my settings 🍺

  - Import a HTML file and watch it magically convert to Markdown

> The overriding design goal for Markdown's

### terminal

1. copy the mybash to /home/<userName>/.mybash

2. edit ~/.bashrc:
    ```sh
    $ nano ~/.bashrc
    ```
    add this line:
    ```sh
    $ source ~/.mybash
    ```
3. install and setup oh my zsh
    #### install zsh
    ```sh
    $ sudo apt-get install zsh
    ```
    ```sh
    $ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```

    #### install plugins
    ```sh
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
    
    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
    
    ```sh
    git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf && ~/.fzf/install
    ```
    
    #### customize
    ```sh
    $ nano ~/.zshrc
    ```
    ```
    ZSH_THEME="robbyrussell"
    plugins=(zsh-syntax-highlighting zsh-autosuggestions)
    ```
4. intall font
    [download font face](https://github.com/powerline/fonts/tree/master/GoMono)
    replcae "windows terminal" file with wwindows terminal settings
    
    
    

Dillinger requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.



First Tab:
```sh
$ node app
```

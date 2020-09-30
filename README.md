# My Bash Terminal Settings 🍺


### terminal

1. install and setup oh my zsh
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
    
    ```sh
    sudo apt install cowsay
    ```
    
    #### customize
    ```sh
    $ nano ~/.zshrc
    ```
    ```
    ZSH_THEME="robbyrussell"
    plugins=(zsh-syntax-highlighting zsh-autosuggestions)
    ```
2. intall font
    [download font face](https://github.com/powerline/fonts/tree/master/GoMono)
    replcae "windows terminal" file with wwindows terminal settings

3. copy the mybash to /home/(userName)/.mybash

4. edit ~/.zshrc:
    ```sh
    $ nano ~/.zshrc
    ```
    add this line:
    ```sh
    $ source ~/.mybash
    ```
    

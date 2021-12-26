# **Azmi's Terminal Setup**

### **Install zsh first**

> https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH

### **Install Oh My Zsh**

> https://github.com/ohmyzsh/ohmyzsh

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### **Install Powerlevel10k Theme**

> https://github.com/romkatv/powerlevel10k

After installed, change p10k settings in ~/.p10k.zsh with config from p10k.zsh.example

### **Install plugins**

- git

> https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git

- Auto Suggestions

> https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh

- Web Search

> https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/web-search

- Copydir

> https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/copydir

- Zsh syntax highlighting

> https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md

### **Edit configuration in .zshrc file**

```sh
nano ~/.zshrc

# change theme to powerlevel10k
ZSH_THEME="powerlevel10k/powerlevel10k"

# add this plugins below to zshrc plugins list

plugins=(
  git
  zsh-autosuggestions
  web-search
  copydir
  zsh-syntax-highlighting
)

# restart zsh terminal
exec zsh
```

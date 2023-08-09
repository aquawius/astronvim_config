# AstroNvim User Configuration Example

A user configuration template for [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

#### Clone AstroNvim

```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
```

#### Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/<your_user>/<your_repository> ~/.config/nvim/lua/user
```

#### Windows Command
> If you are using windows. **Instead of the above two commands, use the following commands**:
> ```powershell
>  # Clone AstroNvim
>  git clone https://github.com/AstroNvim/AstroNvim $env:LOCALAPPDATA\nvim
>  # Clone my config
>  git clone https://github.com/aquawius/astronvim_config.git $env:LOCALAPPDATA\nvim\lua\user
> ```

#### Start Neovim

```shell
nvim
```

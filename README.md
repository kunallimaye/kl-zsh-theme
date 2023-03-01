# Setup

> 1. Clone the repo
   ```
   git clone https://github.com/kunallimaye/kl-zsh-theme ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
   ```
   
> 2. Update the `~/.zshrc` config file
   ```
   # Update Theme
   ZSH_THEME="powerlevel10k/powerlevel10k"
   
   # To customize prompt, run `p10k configure` or edit ~/.p10k.zsh.
   P10K_ZSH=${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k/.p10k.zsh
   [[ ! -f ${P10K_ZSH} ]] || source ${P10K_ZSH}
   ```

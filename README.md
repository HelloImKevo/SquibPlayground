# SquibPlayground
Playground for experimenting with (Ruby) Squib projects.

Squib Project:  
https://github.com/andymeneely/squib

MacOS M1 / M2 Setup Tips:
```shell
brew install rbenv

rbenv init
rbenv install -l
rbenv install 3.0.6
rbenv global 3.0.6
```

Add this to your `~/.zprofile` file:
```
export PATH="$HOME/.rbenv/shims:$PATH"
export PATH="$HOME/.rbenv/bin:$PATH"
```

Download Oh My Zsh here:  
https://ohmyz.sh/

### zsh-allclear

A super tiny plugin (<10 LOC) that clears the terminal when you `cd` into `$HOME`. That's it.

### Installing

#### Oh-My-Zsh

Run the following command

```shell
git clone https://github.com/givensuman/zsh-allclear ${ZSH_CUSTOM:-~/.oh-my-zsh/custom/}/plugins
```

and add `zsh-allclear` to your plugin list in `~/.zshrc`

```
plugins=(
  ...
  zsh-allclear
)
```

#### zplug

Add the following to your `~/.zshrc`

```shell
zplug 'givensuman/zsh-allclear'
```

#### zinit

Add the following to your `~/.zshrc`

```shell
zinit ice deptph "1"
zinit light givensuman/zsh-allclear
```

### License

You know the drill, do whatever you want with this.
# take-fish

**TL;DR**: `take dir/subdir` == `mkdir -vp dir/subdir; cd dir/subdir`

An alias that creates directories then enters into it.

This alias is the inspired by [Oh My Zsh's](https://github.com/robbyrussell/oh-my-zsh/blob/master/lib/functions.zsh#L13) `take`.


## Installation

The easiest way is by using [fisher](https://github.com/jorgebucaran/fisher):
```
fisher add vrcca/take-fish
```

## Usage

Let's say you are about to create a project and want to automatically create the directory structure and enter the last created directory. 

You can simply do this:
```fish
$ take Developer/Elixir/parear
$ pwd
/Users/vrcca/Developer/Elixir/parear
```

Voilà! :)

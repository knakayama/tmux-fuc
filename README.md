tmux-fuc
========

Search Frequently Used Commands

# Description

This tpm plugin shows your frequently used commands (fuc) with peco style. You can quickly search fuc.

# Requirements

* [tmux](https://tmux.github.io/)
* [peco](https://github.com/peco/peco)
* [tpm](https://github.com/tmux-plugins/tpm)
* pbcopy

# Install

Install tpm and add the following line to your `~/.tmux.conf`

```bash
set-option -g @plugin 'knakayama/tmux-fuc'
```

then, press `Prefix + I` in tmux session.

# Usage

First, create your fuc repository like [this](https://github.com/knakayama/my-fuc), and clone the repository to your machine.

```bash
$ git clone path/to/fuc/repo ~/.fuc
```

Default fuc directory path is `~/.fuc`. If you wanto to change the path, set the following line to your `~/.tmux.conf`.

```bash
set-option -g @fuc-path 'path/to/fuc/dir'
```

Default key binding is `Prefix + e`. If you change this key binding, set the following line to your `~/.tmux.conf`.

```bash
set-option -g @fuc-key 'x' # or your favorite key binding
```

# License

MIT

# Author

[knakayama](https://github.com/knakayama)

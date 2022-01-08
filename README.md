# [WIP] Attach Browser Sessions to Tmux Sessions

Plugin that let you have a browser session that is attached to the tmux sessions.

### Dependencies

* Firefox/Chrome/Chromium
* [brotab](https://https://github.com/balta2ar/brotab)]

### Usage

TODO: complete
```tmux.conf
```

### Installation with Tmux Plugin Manager (recommended)

Add plugin to the list of TPM plugins:

```tmux.conf
set -g @plugin 'ofir753/tmux-browser'
```

Press prefix + I to install it.

### Manual Installation

Clone the repo:

```bash
$ git clone https://github.com/ofir753/tmux-browser.git ~/clone/path
```

Add this line to your .tmux.conf:

```tmux.conf
run-shell ~/clone/path/tmux-browser.tmux
```

Reload TMUX environment with:

```bash
$ tmux source-file ~/.tmux.conf
```

### Configurations

#### Option example

Follows same rules as `set-option`

TODO: complete

```tmux.conf
```

### License

[MIT](LICENSE)

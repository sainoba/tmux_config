# 🔧 Install

## Step 1 - Install tmux plugin manager

[Instructions in the tpm repo](https://github.com/tmux-plugins/tpm)

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## Step 2 - Clone my configurations

```bash
mkdir -p "$HOME/.config/tmux
git clone git@github.com:sainoba/tmux_config.git "$HOME/.config/tmux"
```

**⚠This configuration changes the prefix from `<Ctrl>+b` to `<Ctrl+space>`.**

## Step 3 - Install/refresh plugins

The plugins are listed in `"$HOME/.config/tmux"/tmux.conf`

To install/refresh the plugins open tmux and run:

```bash
<Ctrl+space> I
```

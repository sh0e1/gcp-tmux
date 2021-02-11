# gcp-tmux

Google Cloud Platform project status for tmux

![plugin](screenshot.png)

## Installation

### git

Clone this repository to your $HOME/.tmux directory

```
git clone https://github.com/sh0e1/gcp-tmux.git ~/.tmux/gcp-tmux
```

Add the following line to your ~/.tmux.conf

```
set -g status-right "#(/bin/bash ~/.tmux/gcp-tmux/gcp.tmux)"
```

### tpm

It can be installed using the [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

```
set -g status-right "#(/bin/bash ~/.tmux/plugins/gcp-tmux/gcp.tmux)"

set -g @plugin 'tmux-plugins/tpm'
set -g @plugin 'sh0e1/gcp-tmux'

run '~/.tmux/plugins/tpm/tpm'
```

## Licence

[MIT](https://github.com/sh0e1/gcp-tmux/blob/master/LICENSE)

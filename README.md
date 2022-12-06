## Setup Commands

### all
```bash
curl https://raw.githubusercontent.com/Nick-LCY/configs/main/setup-all.sh | bash
```

### basic
```bash
curl https://raw.githubusercontent.com/Nick-LCY/configs/main/basic/.bash_aliases >> ~/.bash_aliases && curl https://raw.githubusercontent.com/Nick-LCY/configs/main/basic/.inputrc >> ~/.inputrc
```

### tmux
```bash
curl https://raw.githubusercontent.com/Nick-LCY/configs/main/tmux/tmux.conf > ~/my-tmux.conf && tmux source-file ~/my-tmux.conf && rm ~/my-tmux.conf
```
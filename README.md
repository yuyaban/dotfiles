# dotfiles
## directory Tree
```
dotfiles
├── README.md
├── dotfiles
│   ├── .tmux.conf
│   ├── .vimrc
│   └── .zshrc
└── scripts
    └── install.sh
```

## Installation
### Step1: clone this repository in your $HOME.
```
git clone git@github.com:YuyaBan/dotfiles.git
```

### Step2: Run install script.
install.sh creates synbolic-link your dotfiles
Warn: install.sh deletes the dotfiles you are currently using
```
sh scrips/install.sh
```
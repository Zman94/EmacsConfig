#VM Config
Files to download on Virtual Machines

#Emacs Installation

Install emacs 24.5

Run
```
git clone https://github.com/Zman94/EmacsConfig.git ~/.emacs.d
mv ~/.emacs.d/.spacemacs ~/
```

Open Emacs

#Bash Installation

Run
```
sudo mv ~/.emacs.d/.bashrc ~/
```

#Git Config Installation

Run
```
sudo mv ~/.emacs.d/.gitconfig ~/
curl -o ~/.git-prompt.sh       -OL cdn.learnenough.com/git-prompt.sh
curl -o ~/.git-completion.bash -OL cdn.learnenough.com/git-completion.bash
```
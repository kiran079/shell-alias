# shell-alias

A list of common aliases that I use. This is a living repository.

To use this in your terminal on mac, run the following to download the files in this repo.
```
git clone https://github.com/kiran079/shell-alias.git "${XDG_CONFIG_HOME:-$HOME/.config}"/shell-alias
```

Then, to have zsh run this on startup, you need to add the source script to your ~/.zshrc file.

Open the zshrc file using your favorite text editor.
```
vim ~/.zshrc
```
Then, add the follow line to the file.
```
source $HOME/.config/shell-alias/.aliases
```

Finally, source the zshrc file, by running the following in your terminal.

```
source ~/.zshrc
```
*Note: Any running terminal may not be updated. You may need to start a new terminal window after running the previous command*

Thats it! Feel free to fork this repository and alias away.

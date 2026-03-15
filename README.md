# dotfiles
My UNIX dotfiles. I'm currently using GNU Stow to deploy them.

Stow is needed to be installed in the system ('sudo apt install stow' por Debian-like systems)

Download the project, enter the folder and user any of the following commands:

- To stow one or more packages: stow alacritty [git nvim bash ...]
- To stow everything: stow *

Upon updates, stow again right after pulling the repo.

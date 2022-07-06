### Useage:
Installing up to date node versions is kinda a pain in the ass on linux distributions like ubuntu because they only support up to ~v11 so I made a list of steps that make it easy to install new versions of node.

### Steps:
1. curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh
2. curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
3. source ~/.bashrc
4. nvm list-remote
5. nvm install (version)
then check your version with node -v

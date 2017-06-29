# Work-environment-install

* 安装iterm2 [地址](http://www.iterm2.com/)

* 安装homebrew /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
(homebrew 会检测 安装Xcode)

* 安装git brew install git
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.br branch

* 安装wget brew install wget

* 安装 zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

* 安装nvm 管理node版本
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
修改 ~/.zshrc
=> Appending nvm source string to /Users/huguoyun/.zshrc
=> Appending bash_completion source string to /Users/huguoyun/.zshrc
=> Close and reopen your terminal to start using nvm or run the following to use it now:

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion

* 安装node (多个版本)
nvm install v6.11.0
nvm install v8.11.0

* 安装nrm 切换npm源
npm install -g nrm

* 安装mysql
brew install mysql

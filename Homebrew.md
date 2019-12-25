#### List installed packages, sorted by last modified data
brew ls -lt

#### Check package information installed by Homebrew
brew info [package_name]

#### This one command will uninstall all the packages install through Homebrew.
brew remove --force $(brew list) --ignore-dependencies

#### To remove unused archives run.
brew cleanup

#### Check system for potential problems.
$ brew doctor
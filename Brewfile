cask_args appdir: "/Applications"

tap 'caskroom/cask'
tap 'caskroom/versions'
tap 'caskroom/fonts'
tap 'homebrew/dupes'
tap 'homebrew/services'

brew 'mas-cli'

#kegonly: need to check linking /path

brew 'openssl'
brew 'curl', args:["with-nghttp2","with-openssl","with-c-ares"]

brew 'fish'
brew 'bash'
brew 'bash-completion'
brew 'grep'

brew 'wget'

brew 'python3'

brew 'caskroom/cask/brew-cask'
brew 'docker' , args: ["with-experimental"]
brew 'git', args: ["with-curl","with-openssl"]

brew 'ansible'

brew 'mongodb'
brew 'gradle'
brew 'htop', args:["with-ncurses"]
brew 'kubernetes-cli'
brew 'pandoc'
brew 'syncthing', restart_service: :changed
brew 'syncthing-inotify'
brew 'ssh-copy-id'

#Override Mac osx comandline tools
#brew  perl
#brew  python
brew 'rsync'
brew 'unzip'
brew 'less'
brew 'make'
brew 'nano'

cask "java" unless system "/usr/libexec/java_home --failfast"

cask 'adobe-creative-cloud'
cask 'atom'
cask 'dashlane'
cask 'google-chrome'
cask 'java'
cask 'intellij-idea-ce'
cask 'mongodb-compass'
cask 'caffeine'
cask 'steam'
cask 'aerial'
cask 'doxie'
cask 'keka'
cask 'docker'
cask 'postman'

#fonts
cask 'font-hack'

mas "Xcode", id: 497799835
mas "Keynote", id: 409183694
mas "Numbers", id: 409203825
mas "Pages", id: 409201541
mas "iMovie", id: 408981434
mas "Pocket", id: 568494494
mas "Evernote", id: 406056744
mas 'Slack', id: 803453959

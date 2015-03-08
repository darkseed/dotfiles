# Usage 'brew bundle Brewfile'

doctor

# Make sure we have the latest packages
update

# Upgrade already installed packages
upgrade

# Add repositories
tap caskroom/cask || true
tap homebrew/binary || true
tap homebrew/completions || true
tap homebrew/python || true
tap homebrew/science || true
tap larsimmisch/avr || true

# Install cask
install brew-cask

install coreutils
install moreutils
install findutils
install dockutil
install gnu-sed --default-names

install osxfuse
install ext2fuse
install ext4fuse

install openvpn

# Install the latest bash
install bash
install bash-completion

# install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
install vim --override-system-vi --with-python --with-ruby
install homebrew/dupes/grep
install homebrew/dupes/screen

# Other usefull binaries
install ack
install ctags
install git
install git-flow
install imagemagick --with-webp
install nmap
install p7zip
install pigz
install webkit2png
install tree
install foremost
install chrome-cli
install spark
install grc

# Python
install python
link --overwrite python

cask doctor
cask install evernote
cask install vlc
cask install google-chrome
cask install google-drive
cask install google-notifier
cask install google-hangouts
cask install iterm2
cask install vlc
cask install virtualbox
cask install the-unarchiver
cask install imageoptim
cask install imagealpha

cleanup
linkapps
prune

# Usage 'brew bundle Brewfile'

# Make sure we have the latest packages
update

# Upgrade already installed packages
upgrade

# Add repositories
tap homebrew/binary || true
tap homebrew/completions || true
tap homebrew/python || true
tap homebrew/science || true
tap larsimmisch/avr || true

install coreutils
install moreutils
install findutils
install gnu-sed --default-names

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

# Python
install python

cleanup

linkapps

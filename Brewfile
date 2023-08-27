#############################################################
# ~/.Brewfile - Software Installs for MacOS                 #
#                                                           #
# List of packages to be installed / updated via Homebrew   #
# Apps are sorted by category                               #
# Be sure to comment out anything you do not need           #
# Usage, run: $ brew bundle --global --file $HOME/.Brewfile #
# Source GH repository: https://github.com/adsiddiq/Brewfile #
# See brew docs for more info: https://docs.brew.sh/Manpage #
#                                                           #
# License: MIT © Adam Siddiq 2022 <>#
#############################################################

# Options
cask_args appdir: '~/Applications', require_sha: true

# Taps (Repositories)
tap 'homebrew/bundle'
tap 'homebrew/core'
tap 'homebrew/services'
tap 'buo/cask-upgrade'
tap 'homebrew/cask-fonts'

# CLI Utilities  
brew 'tree'         # Display directories as trees (with optional color/HTML output)
brew 'git'          # Version controll
brew 'rsync'        # Fast incremental file transfer
brew 'htop'         # Cross-platform interactive process viewer 
brew 'speedtest-cli'# Command line speed test utility
brew 'task'         # Todo + task management
brew 'neofetch'     # Show system data and ditstro info
brew 'youtube-dl'   # Download YouTube videos from the command-line
brew 'yt-dlp'       # Fork of youtube-dl with additional features and fixes
brew 'mas'          # Mac App Store command-line interface (Used for mas apps below)

# Web Browsers
cask 'firefox'
cask 'google-chrome'
cask 'orion'
cask 'microsoft-edge'

# Programming and Development
cask 'visual-studio-code'
cask 'anaconda'   # R and Python environment manager
cask 'rstudio'    # IDE for R 
cask 'spyder'     # IDE for Python
cask 'github'     # Desktop client for GitHub repositories
brew 'docker'     # Pack, ship and run any application as a lightweight container

# Productivity
cask '1password'
cask 'app-cleaner'
cask 'mendeley-reference-manager'
cask 'mactex'         # Full TeX Live distribution with GUI applications
cask 'notion'         # App to write, plan, collaborate, and get organized
cask 'marta'          # Extensible two-pane file manager
cask 'skim'           # PDF reader and note-taking application
cask 'iina'           # Media Player (better than VLC on MacOS)
cask 'google-drive'
cask 'coteditor'      # Just a simple plain-text editor
cask 'the-unarchiver' # File archiver and extractor
cask 'microsoft-auto-update'
cask 'microsoft-office'
cask 'microsoft-teams'
cask 'zoom'

# Other
cask 'messenger'
cask 'whatsapp'
cask 'spotify', args: { require_sha: false } 

# Mac App Store Applications
mas 'Xcode', id: 497799835
mas 'Magnet', id: 441258766
mas 'PDF Squeezer' id: 1502111349

# Fonts
cask 'font-computer-modern'

# END

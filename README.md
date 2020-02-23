# setup-mac

- Apps
  - [GNU Emacs For Mac OS X](https://emacsformacosx.com/)
  - Rocket.Chat
  - Mattermost
  - [Dozer - Hide menubar icons](https://dozermac.com/)
  - [Homebrew](https://brew.sh/)
  - [iTerm2 - macOS Terminal Replacement](https://www.iterm2.com/)
    - https://stackoverflow.com/a/23356086/514411
    - `Preferences -> General` you will notice at the bottom of the panel, there is a setting `Load preferences from a custom folder or URL:`. There is a button next to it `Save settings to Folder`.
  - MenuMeters [yujitach/MenuMeters: my fork of MenuMeters by http://www.ragingmenace.com/software/menumeters/](https://github.com/yujitach/MenuMeters)
  - RunCat
  - Cybozu Desktop
  - RescueTime [RescueTime : Time management software for staying productive and happy in the modern workplace](https://www.rescuetime.com/)
  - [Spectacle](https://www.spectacleapp.com/)
  - Cerebro
  - Camunda Modeler
  - Barrier 2.1.0 [debauchee/barrier: Open-source KVM software](https://github.com/debauchee/barrier)
  - Dynalist
  - Wey
  - MacZip4Win [MacZip4Win | YNOMURA.COM](http://ynomura.com/home/?page_id=116)
  - BitBar [matryer/bitbar: Put the output from any script or program in your Mac OS X Menu Bar](https://github.com/matryer/bitbar)
  - [Keybase](https://keybase.io/docs/the_app/install_macos)
  - Pencil [Home - Pencil Project](http://pencil.evolus.vn/)
  - CleanMyMac X [CleanMyMac X: The Best Mac Cleanup App for macOS. Get a Cleaner Mac in Minutes.](https://macpaw.com/cleanmymac)
  - Skitch.app from AppStore
  - App Cleaner [AppCleaner](https://freemacsoft.net/appcleaner/)
  - DBearver [DBeaver Community | Free Universal Database Tool](https://dbeaver.io/)
  - Insomnia [Insomnia REST Client](https://insomnia.rest/)
  - [Biscuit | A browser so your apps don't get buried in tabs](https://eatbiscuit.com/)
- `defaults write com.apple.finder AppleShowAllFiles TRUE`
- brew install pick up from `brew leaves`
  - see `brew-leaves`
  - `xargs brew install < brew-leaves`
- zsh
  - add `/usr/local/bin/zsh` to `/etc/shells`
  - `chsh` to `/usr/local/bin/zsh`
  - reload completion
    - `autoload -U compinit;compinit -u;rm ~/.zcompdump; compinit`
- gem
  - `sudo gem install license-generator`
- system preferences
  - keyboard
    - enable japanese
  - screen saver
  - desktop picture
  - hot corner
    - both bottom `put display sleep`
    - top right `mission control`
  - security
    - general
      - require password `immediately`...
- dot files
  - zsh
  - tmux
  - emacs
  - aliases
  - ssh
- Files
  - almost all of ~/
    - Documents
    - Downloads
    - Work
    - temporaly copy to ~/mba
- Fonts
  - [tonsky/FiraCode: Monospaced font with programming ligatures](https://github.com/tonsky/FiraCode)
- golang
  - `go get github.com/tokuhirom/git-xlsx-textconv` for diff xlsx

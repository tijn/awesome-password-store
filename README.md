# Awesome password-store

[Pass](https://www.passwordstore.org/) is awesome. And these extensions make it even more so! This is a collection of awesome password-store extensions and interfaces.

Additions and improvements are welcome! Please make pull-requests.

## Contents

- [extensions](#extensions)
  - [auditing](#auditing)
  - [clipboard](#clipboard)
  - [output](#output)
  - [import](#import)
  - [generators](#generators)
  - [All other extensions](#all-other-extensions)
- [Interfaces](#interfaces)
- [Import scripts](#import-scripts)
- [Export scripts](#export-scripts)

## Extensions

### Auditing

* **[pass-age](https://github.com/taylorskalyo/pass-age)** (by [taylorskalyo](https://github.com/taylorskalyo)): A simple pass extension for displaying password age. *(There are two extensions with this name; this one shows the time of the last git commit.)*
* **[pass-age](https://github.com/tijn/pass-age)** (by [tijn](https://github.com/tijn)): A pass extension to show you how long you are using a certain password. *(There are two extensions with this name; this one shows the last time when the first line in a password file changed.)*
* **[pass-audit](https://github.com/benburwell/pass-audit)** (by [benburwell](https://github.com/benburwell)): A pass extension for checking whether your passwords may be compromised. *(There are two extensions with this name; this one checks Have I Been Pwned as well as a local wordlist file.)*
* **[pass-audit](https://github.com/roddhjav/pass-audit)** (by [roddhjav](https://github.com/roddhjav)): A pass extension for auditing your password repository. *(There are two extensions with this name; this one checks Have I Been Pwned and estimates password strength using Dropbox' [zxcvbn](https://blogs.dropbox.com/tech/2012/04/zxcvbn-realistic-password-strength-estimation/) algorithm.)*
* **[pass-hibp](https://gitlab.com/moviuro/pass-hibp/)**: A pass extension that queries the haveibeenpwned.com API.
* **[pass-pwned](https://github.com/alzeih/pass-pwned/)** (by [alzeih](https://github.com/alzeih)): Password-Store extension for Have I Been Pwned? Pwned Passwords v2 API.
* **[pass-pwned](https://github.com/jamesridgway/pass-pwned)** (by [jamesridgway](https://github.com/jamesridgway)): Password-Store extension for Have I Been Pwned? Pwned Passwords v2 API or an offline password hash file of your choosing.
* **[pass-report](https://github.com/Kdecherf/pass-report)**: A pass extension that reports age and length of passwords.

### Clipboard

* **[pass-clip](https://github.com/ibizaman/pass-clip)**: A pass extension that lets you quickly copy to clipboard passwords using fzf or rofi.
* **[pass-extension-pclip](https://gitlab.com/lbischof/pass-extension-pclip)**: Copies meta data into primary clipboard.
* **[pass-extension-wclip](https://github.com/palortoff/pass-extension-wclip)**: a plugin to use wclip on Windows.
* **[pass-sclip](https://github.com/Boldewyn/pass-sclip)**: A pass extension to copy to [screen](https://www.gnu.org/software/screen/)'s paste buffer.
* **[pass-tessen](https://sr.ht/ayushnix/pass-tessen)**: fuzzy data selection and copy-paste from password store

### Output

* **[pass-cl](https://github.com/elcorto/pass-cl)**: password-store extension to copy metadata from multi-line entries.
* **[pass-csv](https://github.com/lahr/pass-csv)**: generate a CSV file from specified key-value pairs in the metadata.
* **[pass-extension-copyq](https://github.com/vy/pass-extension-copyq)**: A pass extension that copies a stored password using copyq.
* **[pass-extension-meta](https://github.com/rjekker/pass-extension-meta)**: password-store extension to retrieve meta-data properties from password files.
* **[pass-extension-tail](https://github.com/palortoff/pass-extension-tail)**: A pass extension to avoid printing the password to the console.

### Import

* **[pass-file](https://github.com/dvogt23/pass-file)** (by [dvogt23](https://github.com/dvogt23)): A pass extension that allows to add files to password-store.
* **[pass-file](https://github.com/lukrop/pass-file)** (by [lukrop](https://github.com/lukrop)): A pass extension for adding arbitrary files to the password store.
* **[pass-import](https://github.com/roddhjav/pass-import)**: a generic importer tool from other password managers.

### Generators

* **[pass-gen](https://passgen.codesections.com/)**: A command-line utility that generates secure, pronounceable passphrases for pass. *(It won't add a new pass command but can be used seamlessly with pass.)*
* **[pass-genphrase](https://github.com/congma/pass-genphrase)**: Passphrase generator extension for pass, the password manager.
* **[pass-qr](https://github.com/codekoala/pass-qr)**: A pass extension that lets you quickly generate a QR code for passwords using fzf or rofi.
* **[pass-ssh](https://github.com/ibizaman/pass-ssh)**: A pass extension that lets you quickly create ssh keypairs and output public keys using fzf or rofi.
* **[pass-totp](https://github.com/muteor/pass-totp)**: TOTP code generator for pass.
* **[pass-words](https://gitlab.com/entrez/pass-words)**: generate Diceware-style mnemonic passwords.

### All other extensions

* **[pass-backup](https://github.com/8go/pass-backup)**: makes making a time-stamped backup simple and easy.
* **[pass-botp](https://github.com/msmol/pass-botp)**: A pass extension for managing TOTP Backup Codes.
* **[pass-coffin](https://sr.ht/ayushnix/pass-coffin)**: hide data inside a signed and encrypted coffin
* **[pass-extension-inc](https://github.com/diginatu/pass-extension-inc)**: A unix pass extension for incremental search.
* **[pass-grave](https://github.com/8go/pass-grave)**: helps you hide all meta-data by placing the whole tree of passwords inside an encrypted grave (like pass-tomb but simpler and more lightweight).
* **[pass-index](https://github.com/sboesebeck/pass-index.git)**: Speed up content search
* **[pass-keybase](https://github.com/mbauhardt/pass-keybase)**: A pass extension to re-encrypt and decrypt pass entries via keybase.
* **[pass-ln](https://github.com/raxod502/pass-ln)**: A pass extension for creating symbolic links.
* **[pass-mount](https://github.com/HXR/pass-mount)**: A pass extension for mounting encrypted filesystems.
* **[pass-open-doc](https://github.com/bergercookie/pass-open-doc)**: Open a file from your Password Store via xdg
* **[pass-otp](https://github.com/tadfisher/pass-otp)**: support for one-time-password (OTP) tokens.
* **[pass-tomb](https://github.com/roddhjav/pass-tomb)**: helps you to keep the whole tree of password encrypted inside a tomb.
* **[pass-update](https://github.com/roddhjav/pass-update)**: an easy flow for updating passwords.
* **[pass-ssh](https://github.com/not-jan/pass-ssh)**: Automatically create an SSH session from a pass entry

## Interfaces

* **[alfred-pass](https://github.com/CGenie/alfred-pass)**: Alfred integration
* **[Android-Password-Store](https://github.com/zeapo/Android-Password-Store)**: Android application compatible with ZX2C4's Pass command line application.
* **[awscli-plugin-passtotp](https://github.com/someone-stole-my-name/awscli-plugin-passtotp)**: AWS CLI plugin to directly talk to pass for OATH-TOTP keys.
* **[browserpass](https://github.com/browserpass/browserpass-extension)**: Chrome & Firefox browser extension for pass.
* **[gnome-pass-search-provider](https://github.com/jle64/gnome-pass-search-provider)**: Pass password manager search provider for gnome-shell.
* **[gopass-tui](https://github.com/leitzler/gopass-tui)**: Terminal UI for pass/gopass.
* **[instantpass](https://github.com/instantos/instantpass)**: an [instantmenu](https://github.com/instantOS/instantMENU) frontend with support for pass-opt and pass-file.
* **[krunner-pass](https://github.com/akermu/krunner-pass)**: Integrates krunner (KDE) with pass.
* **[ob-pass-menu](https://github.com/denimor/ob-pass-menu)**: [Openbox](http://openbox.org/wiki/Main_Page) pipe-menu script that generates an xml menu based on zx2c4-pass storage.
* **[pass-alfred](https://github.com/MatthewWest/pass-alfred)**: Alfred integration
* **[pass-companion](https://github.com/kakolisgay/pass-companion)**: Chrome/Chromium browser extension for pass.
* **[pass_rlded](https://github.com/bergercookie/awesome-albert-plugins/tree/master/plugins/pass_rlded)**: [Albert](https://github.com/albertlauncher/albert) integration
* **[pass-ulauncher](https://github.com/yannishuber/pass-ulauncher)**: Integration for [Ulauncher](https://ulauncher.io/).
* **[pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion)**: pass zsh completion plugin.
* **[pass.applescript](https://git.zx2c4.com/password-store/tree/contrib/pass.applescript)**: OS X integration
* **[Pass for macOS](https://github.com/adur1990/Pass-for-macOS)** macOS wrapper and Safari extension.
* **[passbar](https://gitlab.com/rperce/passbar)** Password Store integration for awesomewm.
* **[passff](https://github.com/passff/passff)**: zx2c4 pass manager extension for Firefox, Chrome and Opera.
* **[passforios](https://github.com/mssun/passforios)**: Pass for iOS - an iOS client compatible with Pass command line application.
* **[PassHUD](https://github.com/mnussbaum/PassHUD)**: A HUD-style interface for pass on macOS.
* **[passman](https://github.com/TheAmazingPT/passman)**: A [dmenu](https://tools.suckless.org/dmenu/) frontend for password-store.
* **[pass-winmenu](https://github.com/geluk/pass-winmenu)**: An easy-to-use Windows interface for pass
* **[passwordstore](https://docs.ansible.com/ansible/latest/plugins/lookup/passwordstore.html)**: Ansible lookup plugin to manage passwords with password-store.
* **[pidgin-zx2c4-pass](https://github.com/denimor/pidgin-zx2c4-pass)**: Plugin that allows to use zx2c4 pass to store passwords (for [pidgin](https://pidgin.im/)).
* **[rofi-pass](https://github.com/carnager/rofi-pass)**: A bash script to handle Simple Password Store in a convenient way using rofi.
* **[simple-pass-alfred](https://github.com/johanthoren/simple-pass-alfred)**: Alfred integration
* **[tessen](https://sr.ht/ayushnix/tessen)**: an interactive menu to autotype and copy pass and gopass data
* **[tmux-pass](https://github.com/rafi/tmux-pass)**: Quick password-store browser with preview using fzf in tmux.
* **[vim-password-store](https://github.com/fourjay/vim-password-store)**: Vim niceties for password store.

## Import scripts

These scripts are not extensions but they can be very useful nontheless.

* **[1password2pass.rb](https://git.zx2c4.com/password-store/tree/contrib/importers/1password2pass.rb)**: Import 1Password txt or 1pif data
* **[firefox_decrypt](https://github.com/Unode/firefox_decrypt)**: Full blown Firefox password interface which supports exporting to pass
* **[fpm2pass.pl:](https://git.zx2c4.com/password-store/tree/contrib/importers/fpm2pass.pl)**: Import Figaro's Password Manager XML data
* **[gorilla2pass.rb](https://git.zx2c4.com/password-store/tree/contrib/importers/gorilla2pass.rb)**: Import Password Gorilla data
* **[kedpm2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/kedpm2pass.py)**: Import Ked Password Manager data
* **[keepass2csv2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/keepass2csv2pass.py)**: Import Keepass2 CSV data
* **[keepass2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/keepass2pass.py)**: Import Keepass2 XML data
* **[keepassx2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/keepassx2pass.py)**: Import KeepassX XML data
* **[kwallet2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/kwallet2pass.py)**: Import KWallet data
* **[lastpass2pass.rb](https://git.zx2c4.com/password-store/tree/contrib/importers/lastpass2pass.rb)**: Import Lastpass CSV data
* **[password-exporter2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/password-exporter2pass.py)**: Import password-exporter data
* **[pwsafe2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/pwsafe2pass.py)**: Import PWSafe data (python version)
* **[pwsafe2pass.sh](https://git.zx2c4.com/password-store/tree/contrib/importers/pwsafe2pass.sh)**: Import PWSafe data
* **[revelation2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/revelation2pass.py)**: Import Revelation Password Manager data
* **[roboform2pass.rb](https://git.zx2c4.com/password-store/tree/contrib/importers/roboform2pass.rb)**: Import Roboform data

## Export scripts

* **[pass-export](https://github.com/dvogt23/pass-export)**: Exports data in csv format

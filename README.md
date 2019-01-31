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

## Extensions

### Auditing

* **[pass-age](https://github.com/taylorskalyo/pass-age)** (by [taylorskalyo](https://github.com/taylorskalyo)): A simple pass extension for displaying password age. *(There are two extensions with this name; this one shows the time of the last git commit.)*
* **[pass-age](https://github.com/tijn/pass-age)** (by [tijn](https://github.com/tijn)): A pass extension to show you how long you are using a certain password. *(There are two extensions with this name; this one shows the last time when the first line in a password file changed.)*
* **[pass-audit](https://github.com/benburwell/pass-audit)** (by [benburwell](https://github.com/benburwell)): A pass extension for checking whether your passwords may be compromised. *(There are two extensions with this name; this one checks Have I Been Pwned as well as a local wordlist file.)*
* **[pass-audit](https://gitlab.com/roddhjav/pass-audit)** (by [roddhjav](https://github.com/roddhjav)): A pass extension for auditing your password repository. *(There are two extensions with this name; this one checks Have I Been Pwned.)*
* **[pass-hibp](https://gitlab.com/moviuro/pass-hibp/)**: A pass extension that queries the haveibeenpwned.com API.
* **[pass-pwned](https://github.com/alzeih/pass-pwned/)** (by [alzeih](https://github.com/alzeih)): Password-Store extension for Have I Been Pwned? Pwned Passwords v2 API.
* **[pass-pwned](https://github.com/jamesridgway/pass-pwned)** (by [jamesridgway](https://github.com/jamesridgway)): Password-Store extension for Have I Been Pwned? Pwned Passwords v2 API or an offline password hash file of your choosing.
* **[pass-report](https://github.com/Kdecherf/pass-report)**: A pass extension that reports age and length of passwords.

### Clipboard

* **[pass-clip](https://github.com/ibizaman/pass-clip)**: A pass extension that lets you quickly copy to clipboard passwords using fzf or rofi.
* **[pass-extension-pclip](https://gitlab.com/lbischof/pass-extension-pclip)**: Copies meta data into primary clipboard.
* **[pass-extension-wclip](https://github.com/palortoff/pass-extension-wclip)**: a plugin to use wclip on Windows.
* **[pass-sclip](https://github.com/Boldewyn/pass-sclip)**: A pass extension to copy to [screen](https://www.gnu.org/software/screen/)'s paste buffer.

### Output

* **[pass-cl](https://github.com/elcorto/pass-cl)**: password-store extension to copy metadata from multi-line entries.
* **[pass-extension-copyq](https://github.com/vy/pass-extension-copyq)**: A pass extension that copies a stored password using copyq.
* **[pass-extension-meta](https://github.com/rjekker/pass-extension-meta)**: password-store extension to retrieve meta-data properties from password files.
* **[pass-extension-tail](https://github.com/palortoff/pass-extension-tail)**: A pass extension to avoid printing the password to the console.

### Import

* **[pass-file](https://github.com/dvogt23/pass-file)** (by [dvogt23](https://github.com/dvogt23)): A pass extension that allows to add files to password-store.
* **[pass-file](https://github.com/lukrop/pass-file)** (by [lukrop](https://github.com/lukrop)): A pass extension for adding arbitary files to the password store.
* **[pass-import](https://github.com/roddhjav/pass-import)**: a generic importer tool from other password managers.

### Generators

* **[pass-gen](https://passgen.codesections.com/)**: A command-line utility that generates secure, pronounceable passphrases for pass. *(It won't add a new pass command but can be used seamlessly with pass.)*
* **[pass-genphrase](https://github.com/congma/pass-genphrase)**: Passphrase generator extension for pass, the password manager.
* **[pass-qr](https://github.com/codekoala/pass-qr)**: A pass extension that lets you quickly generate a QR code for passwords using fzf or rofi.
* **[pass-ssh](https://github.com/ibizaman/pass-ssh)**: A pass extension that lets you quickly create ssh keypairs and output public keys using fzf or rofi.
* **[pass-totp](https://github.com/muteor/pass-totp)**: TOTP code generator for pass.

### All other extensions

* **[pass-botp](https://github.com/msmol/pass-botp)**: A pass extension for managing TOTP Backup Codes.
* **[pass-extension-inc](https://github.com/diginatu/pass-extension-inc)**: A unix pass extension for incremental search.
* **[pass-keybase](https://github.com/mbauhardt/pass-keybase)**: A pass extension to re-encrypt and decrypt pass entries via keybase.
* **[pass-mount](https://github.com/HXR/pass-mount)**: A pass extension for mounting encrypted filesystems.
* **[pass-otp](https://github.com/tadfisher/pass-otp)**: support for one-time-password (OTP) tokens.
* **[pass-tomb](https://github.com/roddhjav/pass-tomb)**: helps you to keep the whole tree of password encrypted inside a tomb.
* **[pass-update](https://gitlab.com/roddhjav/pass-update)**: an easy flow for updating passwords.

## Interfaces

* **[Android-Password-Store](https://github.com/zeapo/Android-Password-Store)**: Android application compatible with ZX2C4's Pass command line application.
* **[browserpass](https://github.com/browserpass/browserpass)**: Chrome & Firefox browser extension for pass.
* **[gnome-pass-search-provider](https://github.com/jle64/gnome-pass-search-provider)**: Pass password manager search provider for gnome-shell.
* **[gopass-tui](https://github.com/leitzler/gopass-tui)**: Terminal UI for pass/gopass.
* **[krunner-pass](https://github.com/akermu/krunner-pass)**: Integrates krunner (KDE) with pass.
* **[ob-pass-menu](https://github.com/denimor/ob-pass-menu)**: [Openbox](http://openbox.org/wiki/Main_Page) pipe-menu script that generates an xml menu based on zx2c4-pass storage.
* **[pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion)**: pass zsh completion plugin.
* **[Passafari](https://github.com/adur1990/Passafari)** Safari app extension for pass.
* **[passff](https://github.com/passff/passff)**: zx2c4 pass manager extension for Firefox, Chrome and Opera.
* **[passforios](https://github.com/mssun/passforios)**: Pass for iOS - an iOS client compatible with Pass command line application.
* **[PassHUD](https://github.com/mnussbaum/PassHUD)**: A HUD-style interface for pass on macOS.
* **[passman](https://github.com/TheAmazingPT/passman)**: A [dmenu](https://tools.suckless.org/dmenu/) frontend for password-store.
* **[pidgin-zx2c4-pass](https://github.com/denimor/pidgin-zx2c4-pass)**: Plugin that allows to use zx2c4 pass to store passwords (for [pidgin](https://pidgin.im/)).
* **[tmux-pass](https://github.com/rafi/tmux-pass)**: Quick password-store browser with preview using fzf in tmux.
* **[vim-password-store](https://github.com/fourjay/vim-password-store)**: Vim niceties for password store.

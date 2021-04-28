**Setp 1** : `sudo chown -R $USER ~/.config/composer/`

**Setp 2** : `composer global require cpriego/valet-linux`

**Setp 3** :`sudo nano ~/.profile`

put below code inside and save
```sh
PATH="$HOME/.config/composer/vendor/bin:$PATH"
```

**Step 4** : `source ~/.profile`

**Step 5** : `sudo apt-get install network-manager libnss3-tools jq xsel`

# Installaion

clone this repository into `~/.config/flexget`

```
git clone https://github.com/jkpark/flexget_config.git ~/.config/flexget
```

### config.yml

fix rss inputs

```
        - rss: { url: 'https://localhost/bbs/rss.php?b=torrent_tv', silent: yes }
        - rss: { url: 'https://localhost/bbs/rss.php?b=torrent_variety', silent: yes }
        - rss: { url: 'https://localhost/bbs/rss.php?b=torrent_docu', silent: yes }
```


### secrets.yml

fix transmission infomation

```
  user: _USERNAME_
  pass: _PASSWORD_
```

### wish.yml

input title what you want to download

```
- '제목'
```


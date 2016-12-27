This will set the nginx `proxy_read_timeout` for your dokku app to 1000 minutes.

## Installation
```
dokku plugin:install https://github.com/investtools/dokku-long-timeout-plugin.git
```

previous versions (0.3.x and below) of dokku require a manual process to install plugins
```
cd /var/lib/dokku/plugins
git clone https://github.com/investtools/dokku-long-timeout-plugin.git
dokku plugins-install
```


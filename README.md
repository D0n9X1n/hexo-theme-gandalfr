# hexo-theme-gandalfr

![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/D0n9x1n/hexo-theme-gandalfr?include_prereleases)

Yet, just another blog theme for Hexo, based on [hexo-theme-apollo](https://github.com/pinggod/hexo-theme-apollo).

### Features
+ Built-in Code highlight support.
+ Built-in hexo-tag-cloud support.
+ More comfortable with large screens.

### Live Demo

You can see from [here: mhexo.github.io](https://mhexo.github.io)

### How to Install
``` bash
# cd to your hexo dir
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive hexo-tag-cloud
git clone https://github.com/MikeCoder/hexo-theme-gandalfr.git themes/gandalfr
cd themes/gandalfr
cp _config.yml.example _config.yml
# modify the config file by yourself
```

### Install Hexo-tag-cloud
This theme depends on [hexo-tag-cloud](https://github.com/MikeCoder/hexo-tag-cloud). You should install this plugin first.

You can see from [Here](https://github.com/MikeCoder/hexo-tag-cloud) to learn how to install hexo-tag-cloud.

## Enable the Theme

modify `_config.yml` to change `theme` to `gandalfr`:

```yaml
theme: gandalfr

# Dependent on the hexo-generator-archive plugin
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## Change the Code Style

modify `_config.yml` to change the codestyle block:

```
# Styles shoule be found in the list: https://highlightjs.org/static/demo/
# use the lowercase letters and replace space with -
codestyle: solarized-light
```

## Update to the newest version
``` bash
cd themes/gandalfr
git pull
```

## Thanks
+ [hexo-theme-apollo](https://github.com/pinggod/hexo-theme-apollo)

## License
See [@LICENSE](./LICENSE)

## TODO
See [@TODO.md](./TODO.md)

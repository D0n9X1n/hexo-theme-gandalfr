#hexo-theme-gandalfr



Yet, just another blog theme for Hexo, based on hexo-theme-apollo.

### Live Demo

You can see from [here: mikecoder.github.io/oj-code](https://mikecoder.github.io/oj-code/)

### How to Install
``` bash
" cd to your hexo dir
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive hexo-tag-cloud
git clone https://github.com/MikeCoder/hexo-theme-gandalfr.git themes/gandalfr
```

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

## Update to the newest version
``` bash
cd themes/gandalfr
git pull
```

## Thanks
+ [hexo-theme-apollo](https://github.com/pinggod/hexo-theme-apollo)

## License
See [@LICENSE](./LICENSE)

## Changes

This fork uses Pug instead of the Jade templating engine.

![hexo-theme-apollo](https://cloud.githubusercontent.com/assets/9530963/13026956/08e76eca-d277-11e5-8bfc-2e80cea20a0d.png)

## Documentation

- [中文文档](https://github.com/pinggod/hexo-theme-apollo/blob/master/doc%2Fdoc-zh.md)
- [Document](https://github.com/pinggod/hexo-theme-apollo/blob/master/doc%2Fdoc-en.md)

## Contribution

The project no longer accepts new features or pull request, for all creative ideas please create a fork.

## Installation

[![asciicast](https://asciinema.org/a/emrvroa9054hz6k8ise0uxh2u.png)](https://asciinema.org/a/emrvroa9054hz6k8ise0uxh2u)

``` bash
hexo init Blog
cd Blog
npm install
npm install --save hexo-render-pug hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git clone https://github.com/plck/hexo-theme-apollo.git themes/apollo
```

## Configuration

Modify the `theme` configuration item for` _config.yml` to `apollo`:

```yaml
theme: apollo

# To show all articles on the archive page
# you need to install the hexo-generator-archive plug-in support
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## Update

``` bash
cd themes/apollo
git pull
```

## License

MIT

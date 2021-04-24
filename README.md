# ShowFolio theme for Hugo

![Latest Release](https://img.shields.io/github/tag/apvarun/showfolio-hugo-theme.svg)
![ShowFolio hugo theme](https://img.shields.io/github/license/apvarun/showfolio-hugo-theme)
![Hugo generator](https://img.shields.io/badge/generator-hugo-brightgreen)

ShowFolio is a modern portfolio theme for your Hugo site.

![Preview](https://github.com/apvarun/showfolio-hugo-theme/blob/master/images/screenshot.png)

Features:

- Responsive content
- Social links

## Get the theme

Run from the root of your Hugo site:

```sh
git clone https://github.com/apvarun/showfolio-hugo-theme.git themes/showfolio
```

Alternatively, you can include this repository as a [git submodule](https://git-scm.com/docs/gitsubmodules). This makes it easier to update this theme if you have your Hugo site in git as well:

```sh
git submodule add https://github.com/apvarun/showfolio-hugo-theme.git themes/showfolio
```

## Preview the theme

ShowFolio theme ships with an fully configured example site. For a quick preview:

```sh
cd themes/showfolio/exampleSite/
hugo serve --themesDir ../..
```

Then visit `http://localhost:1313/` in your browser to view the example site.

## Add content

The following explains how to add content to your Hugo site. You can find sample content in the `exampleSite/` folder.

### Structure:

    .
    ├── ...
    ├── projects       # Section Name
    │   ├── project1   # Project 1
    │   ├── project2   # Project 2
    │   └── _index     # (optional) Customize section name &
    │                  # default image for section contents
    └── ...

## Configure your site

From `exampleSite/`, copy `config.toml` to the root folder of your Hugo site and change the fields as you like. Helpful comments are provided.

## Menu

Menu in ShowFolio theme is auto-generated from the sections inside your content folder.

You can also add a custom menu item using the `config.toml` and disable auto-generated sections if not required. Refer config in [exampleSite](https://github.com/apvarun/showfolio-hugo-theme/blob/master/exampleSite/config.toml)

## Google Analytics

Set `googleAnalytics` in `config.toml` to activate Hugo's [internal Google Analytics template](https://gohugo.io/templates/internal/#google-analytics).

## Issues

If you have a question, please [open an issue](https://github.com/apvarun/showfolio-hugo-theme/issues) for help and to help those who come after you. The more information you can provide, the better!

## Contributing

Contributions are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

Licensed under [MIT](LICENSE)
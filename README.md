# Lightbi 

Lightbi is a minimal and clean blog theme for Hugo.

## Live Demo

[lightbi-hugo-theme.netlify.app](https://lightbi-hugo-theme.netlify.app/)

![LightBi Hugo Theme Screenshot](https://raw.githubusercontent.com/binokochumolsundokim/lightbi-hugo/master/images/screenshot.png)

## Features

### General
- Three sections for content:
    - Blog
    - Notes
    - Collections (Newsletter)
- Responsive, mobile-first design.
- Card based theme.
- Menu location indicator.
- Multilingual support. (with language selector)
- Taxonomies.
- Light/Dark theme (automatic theme switch a/c to browser theme and theme-switch button).
- Google Analytics.
- SEO Friendly.
- Commit SHA on the footer.
- Self Hosted assets for GDPR / EU-DSGVO compliance.
- Beautiful icons with Bootstrap Icons.

### Page
- Other Posts suggestion below a post
- Social-Media Share buttons on posts.
- Syntax highlighting.
- Cover image for each post (with Responsive image support).

## Installation

Install Hugo and create a new site. See [the Hugo documentation](https://gohugo.io/getting-started/quick-start/) for details.

```
hugo new site <name of site>
cd <name of site>
git init
git submodule add https://github.com/binokochumolsundokim/lightbi-hugo themes/lightbi-hugo
echo "theme = 'lightbi-hugo'" >> config.toml
hugo server
```

After the above copy the contents of `exampleSite` to the `content` folder in your website.

## For more

Checkout the [wiki](https://github.com/binokochumolsundokim/lightbi-hugo/wiki) page for detailed documentation of the theme features.

## Credits

- [Beautiful Hugo](https://github.com/halogenica/beautifulhugo) from which Lightbi was forked.
- [Unsplash](https://unsplash.com/) for Images.

## About

This is an adaptation of the [Beautiful Hugo](https://github.com/halogenica/beautifulhugo) by [Michael Romero](https://github.com/halogenica). It supports most of the features of the original theme, and many new features. It has diverged from the original theme over time, with several updates.

## License

MIT Licensed, see [LICENSE](https://github.com/binokochumolsundokim/lightbi-hugo/blob/master/LICENSE).


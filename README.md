# _Links_ theme

Theme for [Cecil](https://cecil.app), powered by [Tailwind CSS](https://tailwindcss.com) and [Font Awesome](https://fontawesome.com).

![Screenshot](./docs/screenshot.png)

## Features

- Template blocks
- Dark mode
- Etc.

## Installation

```bash
composer require cecil/theme-links
```

> Or [download the latest archive](https://github.com/Cecilapp/theme-links/releases/latest/) and uncompress its content in `themes/links`.

## Usage

Add `links` in the `theme` section of the configuration:

```yaml
theme:
  - links
```

## Customization

Templates only use semantic classes (`.layout`, `.header`, `.avatar`, `.site-title`, `.site-baseline`, `.content`, `.footer`, `.buttons`, `.button`, `.button-link`, `.button-icon`, `.button-favicon`, `.button-title`, `.button-media`, `.social`, `.social-icon`, `.social-<name>`, etc.): their appearance is defined in `assets/tailwind.css` and can be overridden in your own `assets/tailwind.css`.

## Development

### Install `tailwind-builder`

```bash
composer require aligny/tailwind-builder
```

### Rebuild CSS

```bash
vendor/bin/tailwind-builder assets/tailwind.css --minify
```

## License

 _Links_ theme is a free software distributed under the terms of the MIT license.

© [Arnaud Ligny](https://arnaudligny.fr)

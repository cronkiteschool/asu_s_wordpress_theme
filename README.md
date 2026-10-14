# ASU `_s` WordPress Theme

A classic WordPress theme created for Arizona State University sites at the Cronkite School. It is based on Automattic's [`_s` (Underscores)](https://underscores.me/) starter theme and includes ASU-oriented branding, header, footer, navigation, and Customizer options.

> **Legacy project:** this theme reflects an earlier generation of ASU web standards and the classic WordPress theme architecture. Evaluate current ASU brand, accessibility, browser, PHP, and WordPress requirements before using it on a new site.

## Included functionality

- Responsive one- and two-column layouts
- ASU-styled header, footer, navigation, and search
- WordPress Customizer integration
- Custom header support
- Widget-ready sidebar and standard post/page templates
- Jetpack and WordPress.com compatibility helpers inherited from `_s`
- Sass source plus compiled CSS

## Installation

1. Download or clone the repository.
2. Place the theme directory in `wp-content/themes/asu_s_wordpress_theme` or upload a ZIP through **Appearance → Themes → Add New**.
3. Activate **asu_s_wordpress_theme**.
4. Open **Appearance → Customize** to configure the site identity, menus, header, and theme options.

## Development

The compiled theme stylesheet is [`style.css`](style.css), with source styles in [`sass/style.scss`](sass/style.scss). This repository does not include a current package manifest or documented build command, so contributors should verify the Sass toolchain before changing generated CSS.

Follow the WordPress coding conventions described in [`CONTRIBUTING.md`](CONTRIBUTING.md). Test changes against the WordPress and PHP versions used by the target site, with particular attention to responsive navigation and keyboard access.

The obsolete historical Travis CI configuration has been retired. No hosted CI workflow is currently configured.

## Upstream projects and assets

- [_s / Underscores](https://underscores.me/) — GPL-2.0-or-later
- [Font Awesome](https://fontawesome.com/) — icon fonts and CSS under their respective licenses
- [Roboto](https://fonts.google.com/specimen/Roboto) — SIL Open Font License
- [ASU Web Standards WordPress Theme](https://github.com/gios-asu/ASU-Web-Standards-Wordpress-Theme)
- [ASU Web Standards Bootstrap](https://github.com/gios-asu/ASU-Web-Standards-Bootstrap)

## License

GPL-2.0-or-later, consistent with WordPress and Underscores. See [`LICENSE`](LICENSE).


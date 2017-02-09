# Bolt Bootstrap Examples Theme

Bootstrap examples integrates all examples on the bootstrap into a twig theme for Bolt. Have a look at the [Bootstrap 4 Alpha Website](https://v4-alpha.getbootstrap.com/) for more info about Bootstrap.

## What's included?
All examples from Bootstrap are included as twig templates. Use them as you like.


## Usage
### Lay out
Because some of the examples are pretty similar they have been grouped into a set of options, the other examples are available as a layout. (except for sign-in obviously)
- standard *(Starter, (Narrow-) Jumbotron, navbar, static top navbar, fixed navbar, justified nav)*
- album
- cover
- carousel
- blog
- dashboard

### Options
These options are mainly for customizing the standard lay out, but can also be used to customize the other lay outs to your needs. The **default** option refers to how the bootstrap example was made.

```YAML
layout:
    # standard, album, cover, carousel, blog, dashboard
    style:
    # default, wide or narrow
    width:

# default, yes or no
singlepage: default


navbar:
    # Possible options: default, no, top, sticky
    position: default
    # default, narrow or wide
    width: default
    # default (left-aligned) , justified or right-aligned
    alignment: default

footer:
    # default (no) or yes
    sticky: default

    # default (no) or yes
offcanvas: default
```
# Installation

Do not install, still in development.
<!-- To install this theme, simply search for 'bs4examples' in Bolt's backend, and
click the buttons.

Alternatively, download the `.zip` or `.tgz` file from the [oekeur/bolt-
foundation-theme Github repository](https://github.com/oekeur/bolt-
foundation-theme/releases). Extract the file, and place the `bs4examples` folder
in your `theme` folder. Don't forget to set `theme: bs4examples` in your
`config.yml` file. -->

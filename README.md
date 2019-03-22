
# Rivendell REC template

Rivendell is a starter responsive template for REC, it comes with:

- Pre-installed on new sites **- coming soon**
- Fully responsive, extending the responsive-base template just like responsive-site template
- SCSS/Sass support
- A clean organised structure for your code
- owlCarousel2 pre installed
- Lato font by default
- Cleaner default Header & Footer layouts
- Ckeditor content areas now display images as inline-blocks by default
- & more, have a browse round the files to see

### Folder structure:

    .
    ├── css
    │   ├── site.css.twig               # On this template, we only use this file to load in your site.scss file
    │   └── themes
    │       ├── ckeditor.css.twig       # Override default style in ckeditor
    │       └── default.css.twig        # Blank to remove default use of Edit Colours area
    ├── html
    │   ├── main.html.twig              # Include libs such as the font & owlCarousel
    │   └── sections                    # Sections of the site html
    │       ├── footer.html.twig
    │       └── header.html.twig
    ├── js
    │   ├── global.js                   # Js you want to run on all pages
    │   ├── modules                     # Folder to put more specific js files into
    │   └── site.js.twig                # Load in all your js files here
    ├── README.md
    ├── scss
    │   ├── base.scss                   # Default styling such as fonts etc.
    │   ├── layout                      # Layout / design files for site
    │   │   ├── footer.scss
    │   │   ├── header.scss
    │   │   ├── header-nav.scss
    │   │   └── middle.scss
    │   ├── mixins.scss                 # Useful functions to help build faster
    │   ├── modules
    │   │   ├── header-search.scss      # Makes the search button design simpler
    │   │   ├── modal.scss              # Default colours for modal header
    │   │   └── nav-flexbox.scss        # Make the nav flex to full width
    │   ├── pages.scss                  # Page specific styles
    │   ├── site.scss                   # All your SCSS imports
    │   └── vars.scss                   # Define default colours, fonts etc.
    └── template_config.json

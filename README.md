
# Rivendell REC template

Rivendell is a starter responsive template for REC, it comes with:

- Pre-installed on new sites **- coming soon**
- Fully responsive, extending the responsive-base template just like responsive-site template
- SCSS/Sass support
- A clean organised structure for your code
- owlCarousel2 pre installed

### Folder structure:

    css/
        site.css.twig   Loaded by REC, it loads your site.scss file*
    scss/
        site.scss       Main file to manage importing all your scss files
        vars.scss       Common variables such as colours, fonts etc.
        mixins.scss     Useful functions to help build faster
        base.scss       Default styling such as fonts
        layout/
            header.scss
            middle.scss
            footer.scss
        modules/
            modal.scss  An example module
        pages.scss      Page specific style
    js/
        site.js.twig  
        global.js
        modules/
            .gitkeep
    html/
        main.html.twig
    .vscode/
        sftp.json
    template_config.json
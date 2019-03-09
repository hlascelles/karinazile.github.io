# read the docs
https://phlow.github.io/feeling-responsive/documentation/

# run local server
	jekyll serve --config _config.yml,_config_dev.yml



# To make internal links, just use a permalink like this
	url: /getting-started/

# To change colors see 
	sass/_01_settings_colors.scss


# Constructing beautiful layouts
https://foundation.zurb.com/sites/docs/v/5.5.3/components/grid.html


## 1. includes for templates.

All includes with `_` are used for templates, like for example the `_head.html` or `_footer.html`.



## 2. includes as commands example

{% include alert success="Yay! you did it!" %}

{% include gallery %}


## Make images of appropriate size
convert DSC_0003.JPG -define jpeg:extent=300kb buttermilk_pancakes.jpg
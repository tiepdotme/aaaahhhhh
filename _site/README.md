# Four A's Five H's: A Jekyll theme for E-Commerce with Snipcart 

![config file](/assets/readme/4a5h_homepage.png)

_aaaahhhhh_ is an eCommerce theme for the static site generator [Jekyll](https://jekyllrb.com/), and with a shopping and checkout cart platform by [SnipCart](https://snipcart.com/).

---

## You will need a [SnipCart](https://snipcart.com/) account in order to use this theme for eCommerce



![config file](/assets/readme/snipcart_api.png)

After you've installed the Theme you'll need to fill out the `_config.yml` with your profile information, Google Analytics, and Snipcart API key.


The only installed plug-in is [compress_images](https://github.com/valerijaspasojevic/jekyll-compress-images).

You can see a working version of the theme at the [Four A's Five H's](https://www.aaaahhhhh.com/) webshop, which was the original development project for the theme.

The theme is built with speed, SEO, and accessibility in mind, and it's doing well but has some room for improvement in the performance, best practices and speed categeries. 

## Here's a basic product page measured by [Lighthouse](https://lighthouse-dot-webdotdevsite.appspot.com/lh/html?url=https://www.aaaahhhhh.com/).


![Lighthouse](/assets/readme/lightspeed-1.png)

 Most, if not all, of the performance losses are from third party scripts, of which there are very few (Snipcart, Google Analytics, FontAwesome, Google Fonts) 
 
 Note that the performance rating decreases by more than 10 points if you use the video embed feature of the theme (vimeo and youtube are supported), and image optimizations will also have an effect.


## PageSpeed Insights, Desktop

![page speed insights](/assets/readme/pagespeed.png)

Page speed insights for mobile devices is `85` on a basic product page, desktop devices rates at `100` :point_up:


## Schema Ouptut for Products

![Schema](/assets/readme/schema.png)

Product pages have Schema output for products, but without the suggested review and rating fields beacuse the theme doesn't currently support those features.

The theme example at [Four A's Five H's](https://www.aaaahhhhh.com/) is deployed through [Netlify](https://www.netlify.com/). 

I'm planning to add [Netlify CMS](https://www.netlifycms.org/) to the theme in the near future, and the post pages have yet to be developed.

Reach out if you have any questions, suggestions, or would like to contribute to the project

[Discoform](mailto:hello@discoform.com?subject=Four%20A's%20Five%20H's%20theme)
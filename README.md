## Jasper Shopify Theme

### WINDOWS

##### Generating _scripts.min.js.liquid_
```sh
ng-annotate -a scripts.js.liquid > scripts.min.js.liquid && uglifyjs scripts.min.js.liquid -o scripts.min.js.liquid --compress sequences=false --mangle
```
    
##### Generating _vendor.min.js_
```sh
type modernizr.min.js angular.min.js angular-animate.min.js angular-cookies.min.js angular-sanitize.min.js angular-touch.min.js es6-promise.auto.min.js imagesLoaded.min.js popper.min.js sticky-kit.min.js perfect-scrollbar.min.js fastclick.min.js scrollreveal.min.js tether.min.js bootstrap.min.js angular-notify.min.js masonry.pkgd.min.js ui-bootstrap-custom-tpls-2.5.0.min.js flickity.pkgd.min.js flickity-imagesloaded.js angular-flickity.min.js ng-map.min.js instafeed.min.js ngDialog.min.js wip-image-zoom.min.js wip-youtube.min.js angular-video-background.min.js jquery.currencies.min.js > vendor.min.js
```

##### Generating _vendor.min.css.liquid_
```sh
type jasper-iconfont.css.liquid animate.min.css ngDialog.min.css perfect-scrollbar.min.css ui-bootstrap-custom-2.5.0-csp.css wip-image-zoom.min.css wip-youtube.min.css flags.css > vendor.min.css.liquid
```

### MAC OS

##### Generating _scripts.min.js.liquid_
```sh
ng-annotate -a scripts.js.liquid > scripts.min.js.liquid && uglifyjs scripts.min.js.liquid -o scripts.min.js.liquid --compress sequences=false --mangle
```

##### Generating _vendor.min.js_
```sh
cat modernizr.min.js angular.min.js angular-animate.min.js angular-cookies.min.js angular-sanitize.min.js angular-touch.min.js es6-promise.auto.min.js imagesLoaded.min.js popper.min.js sticky-kit.min.js perfect-scrollbar.min.js fastclick.min.js scrollreveal.min.js tether.min.js bootstrap.min.js angular-notify.min.js masonry.pkgd.min.js ui-bootstrap-custom-tpls-2.5.0.min.js flickity.pkgd.min.js flickity-imagesloaded.js angular-flickity.min.js ng-map.min.js instafeed.min.js ngDialog.min.js wip-image-zoom.min.js wip-youtube.min.js angular-video-background.min.js jquery.currencies.min.js > vendor.min.js
```

##### Generating _vendor.min.css.liquid_
```sh
cat jasper-iconfont.css.liquid animate.min.css ngDialog.min.css perfect-scrollbar.min.css ui-bootstrap-custom-2.5.0-csp.css wip-image-zoom.min.css wip-youtube.min.css flags.css > vendor.min.css.liquid
```

#
##### Requirements
| Package | URL |
| ------ | ------ |
| ng-annotate | https://github.com/olov/ng-annotate |
| uglifyjs | https://github.com/mishoo/UglifyJS2 |


#
##### Demos
| Name | URL |
| ------ | ------ |
| Demo 1 | http://jasper-theme.myshopify.com/?preview_theme_id=179294852 |
| Demo 2 | http://jasper-theme.myshopify.com/?preview_theme_id=179294980 |
| Demo 3 | http://jasper-theme.myshopify.com/?preview_theme_id=179295108 |
| Demo 4 | http://jasper-theme.myshopify.com/?preview_theme_id=179295556 |
| Demo 5 | http://jasper-theme.myshopify.com/?preview_theme_id=179296132 |
| Demo 6 | http://jasper-theme.myshopify.com/?preview_theme_id=179296196 |
| Demo 7 | http://jasper-theme.myshopify.com/?preview_theme_id=179297156 |
| Demo 8 | http://jasper-theme.myshopify.com/?preview_theme_id=179297220 |
| Demo 9 | http://jasper-theme.myshopify.com/?preview_theme_id=179297284 |
| Demo 10| http://jasper-theme.myshopify.com/?preview_theme_id=179297412 |
| Demo 11| http://jasper-theme.myshopify.com/?preview_theme_id=179297540 |
| Demo 12| http://jasper-theme.myshopify.com/?preview_theme_id=179297668 |
| Demo 13| http://jasper-theme.myshopify.com/?preview_theme_id=179297860 |


#
##### Sample Style Variations for Demo 12
| Name | URL |
| ------ | ------ |
| Alia (Light) - Demo 12 | http://jasper-theme.myshopify.com/?preview_theme_id=180117444 |
| Bello (Light) - Demo 12 | http://jasper-theme.myshopify.com/?preview_theme_id=180118020 |
| Yoyo (Light) - Demo 12 | http://jasper-theme.myshopify.com/?preview_theme_id=180118788 |
| Machu Picchu (Light) - Demo 12 | http://jasper-theme.myshopify.com/?preview_theme_id=180118404 |
| Royalty (Dark) - Demo 12 | http://jasper-theme.myshopify.com/?preview_theme_id=180118148 |
| Entrapped (Dark) - Demo 12 | http://jasper-theme.myshopify.com/?preview_theme_id=180118596 |

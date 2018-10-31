# hugo-Robotico-theme

A stripped down,  [alageek](https://github.com/gkmngrgn/hugo-alageek-theme/tree/a7789a01391c9357fba13704379089e8799adad8) based theme with an added portfolio/light-box gallery for artists/photographers to display their work.  Responsive with Bootstrap 4, single page support, Latex support, and more.  

## Dependencies
* Bootstrap 4.1.3
* Highlight.js 9.12.0
* Jquery slim 3.3.1
* Progressively 1.2.5
* Webfont 1.6.28
* Ekko-lightbox 5.3.0

## Configuration
All features can be accessed by adding code to your config.toml
* See the example site to get an idea of how to use the available params.  

For your home page, create and edit an `_index.md` file with your content.

### Gallery setup
In your config.toml, you can easily add images to your gallery.  Here is an example:
```
[[params.portfolio]]

link = "img/portfolio/example_01.jpg"

[[params.portfolio]]

link = "/img/portfolio/example_02.jpg"

[[params.portfolio]]

link = "/img/portfolio/example_03.jpg"
```
This will import a relative URL, so be sure to use the appropriate file path for your images.  

## License
MIT License...check out the LICENSE.md for more info.  

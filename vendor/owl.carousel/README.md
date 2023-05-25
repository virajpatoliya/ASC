# Owl Carousel 2

Touch enabled [jQuery](https://jquery.com/) plugin that lets you create a beautiful, responsive carousel slider. **To get started, check out https://owlcarousel2.github.io/OwlCarousel2/.**

**Notice:** The old Owl Carousel site (owlgraphic [dot] com) is no longer in use. Please delete all references to this in bookmarks and your own products' documentation as it's being used for malicious purposes.

## Quick start

### Install

This package can be installed with:

- [npm](https://www.npmjs.com/package/owl.carousel): `npm install --save owl.carousel` or `yarn add owl.carousel jquery`
- [bower](http://bower.io/search/?q=owl.carousel): `bower install --save owl.carousel`

Or download the [latest release](https://github.com/OwlCarousel2/OwlCarousel2/releases).

### Load

#### Webpack

Add jQuery via the "webpack.ProvidePlugin" to your webpack configuration:
    
    const webpack = require('webpack');
    
    //...
    plugins: [
        new webpack.ProvidePlugin({
          $: 'jquery',
          jQuery: 'jquery',
          'window.jQuery': 'jquery'
        }),
    ],
    //...

Load the required stylesheet and JS:

```js
import 'owl.carousel/dist/assets/owl.carousel.css';
import 'owl.carousel';
```

#### Static HTML

Put the required stylesheet at the [top](https://developer.yahoo.com/performance/rules.html#css_top) of your markup:

```html
<link rel="stylesheet" href="/node_modules/owl.carousel/dist/assets/owl.carousel.min.css" />
```

```html
<link rel="stylesheet" href="/bower_components/owl.carousel/dist/assets/owl.carousel.min.css" />
```

**NOTE:** If you want to use the default navigation styles, you will also need to include `owl.theme.default.css`.


Put the script at the [bottom](https://developer.yahoo.com/performance/rules.html#js_bottom) of your markup right after jQuery:

```html
<script src="/node_modules/jquery/dist/jquery.js"></script>
<script src="/node_modules/owl.carousel/dist/owl.carousel.min.js"></script>
```

```html
<script src="/bower_components/jquery/dist/jquery.js"></script>
<script src="/bower_components/owl.carousel/dist/owl.carousel.min.js"></script>
```

### Usage

Wrap your items (`div`, `a`, `img`, `span`, `li` etc.) with a container element (`div`, `ul` etc.). Only the class `owl-carousel` is mandatory to apply proper styles:

```html
<div class="owl-carousel owl-theme">
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
</div>
```
**NOTE:** The `owl-theme` class is optional, but without it, you will need to style navigation features on your own.


Call the [plugin](https://learn.jquery.com/plugins/) function and your carousel is ready.

```javascript
$(document).ready(function(){
  $('.owl-carousel').owlCarousel();
});
```

## Documentation

The documentation, included in this repo in the root directory, is built with [Assemble](http://assemble.io/) and publicly available at https://owlcarousel2.github.io/OwlCarousel2/. The documentation may also be run locally.

## Building

This package comes with [Grunt](http://gruntjs.com/) and [Bower](http://bower.io/). The following tasks are available:

  * `default` compiles the CSS and JS into `/dist` and builds the doc.
  * `dist` compiles the CSS and JS into `/dist` only.
  * `watch` watches source files and builds them automatically whenever you save.
  * `test` runs [JSHint](http://www.jshint.com/) and [QUnit](http://qunitjs.com/) tests headlessly in [PhantomJS](http://phantomjs.org/).

To define which plugins are build into the distribution just edit `/_config.json` to fit your needs.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md).

## Roadmap

Please make sure to check out our [Roadmap Discussion](https://github.com/OwlCarousel2/OwlCarousel2/issues/1756).


## License

The code and the documentation are released under the [MIT License](LICENSE).








<div class="owl-carousel owl-carousel-light owl-carousel-light-init-fadeIn owl-theme manual dots-inside dots-horizontal-center custom-dots-style-1 show-dots-hover show-dots-xs nav-style-1 nav-inside nav-inside-plus nav-dark nav-lg nav-font-size-lg show-nav-hover mb-0 dots-color carousel slide corousal-inner" role="" id="rotating_photos" data-bs-ride="carousel" data-plugin-options="{'autoplayTimeout': 7000}" data-dynamic-height="['645px','645px','645px','550px','500px']" style="height: 645px;">
					<div class="owl-stage-outer">
						<div class="owl-stage">
											
							<!-- Carousel Slide 1 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0"  data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image1.jpg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row align-items-center h-100">
										
									</div>
								</div>
							</div>
							
							<!-- Carousel Slide 2 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0" data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image2.jpg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row justify-content-center align-items-center h-100">
							
									</div>
								</div>
							</div>
							
							<!-- Carousel Slide 3 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0"   data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image3.jpg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row justify-content-center align-items-center h-100">
							
									</div>
								</div>
							</div>


							<!-- Carousel Slide 5 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0"  data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image5.jpeg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row justify-content-center align-items-center h-100">
							
									</div>
								</div>
							</div>

							<!-- Carousel Slide 6 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0"   data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image6.jpeg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row justify-content-center align-items-center h-100">
							
									</div>
								</div>
							</div>

							<!-- Carousel Slide 7 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0"  data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image7.jpeg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row justify-content-center align-items-center h-100">
							
									</div>
								</div>
							</div>

							<!-- Carousel Slide 8 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0"  data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image8.jpeg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row justify-content-center align-items-center h-100">
							
									</div>
								</div>
							</div>

							<!-- Carousel Slide 9 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0"  data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image9.jpeg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row justify-content-center align-items-center h-100">
							
									</div>
								</div>
							</div>

							<!-- Carousel Slide 10 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0"   data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image10.jpeg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row justify-content-center align-items-center h-100">
							
									</div>
								</div>
							</div>

							<!-- Carousel Slide 11 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0" data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image11.jpg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row justify-content-center align-items-center h-100">
							
									</div>
								</div>
							</div>

							<!-- Carousel Slide 12 -->
							<div class="owl-item position-relative overflow-hidden">
								<div class="background-image-wrapper position-absolute top-0 left-0 right-0 bottom-0"   data-plugin-options="{'minWindowWidth': 0}" data-carousel-onchange-show style="background-image: url(img1/about/image12.jpg); background-size: cover; background-position: center;"></div>
								<div class="container position-relative z-index-3 h-100 pb-5 pb-sm-0">
									<div class="row justify-content-center align-items-center h-100">
							
									</div>
								</div>
							</div>

							
						</div>
						<button class="carousel-control-prev" type="button" data-bs-target="#rotating_photos" data-bs-slide="prev">
							<span class="carousel-control-prev-icon" aria-hidden="true"></span>
							<span class="visually-hidden">Previous</span>
						  </button>
						  <button class="carousel-control-next" type="button" data-bs-target="#rotating_photos" data-bs-slide="next">
							<span class="carousel-control-next-icon" aria-hidden="true"></span>
							<span class="visually-hidden">Next</span>
						</button>
					</div>
				
					<div class="owl-dots mb-5">
						<button role="button" class="owl-dot active" style="color: blue !important;" ><span></span></button>
						<button role="button" class="owl-dot"><span></span></button>
						<button role="button" class="owl-dot"><span></span></button>
						<button role="button" class="owl-dot"><span></span></button>
						<button role="button" class="owl-dot"><span></span></button>
						<button role="button" class="owl-dot"><span></span></button>
						<button role="button" class="owl-dot"><span></span></button>
						<button role="button" class="owl-dot"><span></span></button>
						<button role="button" class="owl-dot"><span></span></button>
						<button role="button" class="owl-dot"><span></span></button>
						<button role="button" class="owl-dot"><span></span></button>
					</div>
				</div>
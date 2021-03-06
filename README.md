mantra.am
=========

Read. Code. Write. Repeat.

List of personal front-end best practice.

**Content**

- my CSS conventions
  - BEM
  - Idiomatic CSS
  - js-delimited classes
  - OOCSS
  - CSS Code smell 
- Web page performance
  - Images and CSS sprites
  - Checking the performance
- Responsive must
- QA
- WordPress workflow
- Patterns
- Other
- Links

=========

# My CSS conventions

##BEM 
- http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/

```css
.block
.block__element
.block--modifier
.block__element--modifier
.block-name__element

.person 
.person__hand 
.person__nails 
.person__hand__nails 
```

##Idiomatic CSS
- use the principles when writing CSS - https://github.com/necolas/idiomatic-css

##use JS- delimited classes

classes that are purely for js use

```javascript
.js-classs
```
##OOCSS
Worth bothering?

##Avoid code smell
- http://csswizardry.com/2012/11/code-smells-in-css/
- http://www.creativebloq.com/css3/avoid-css-mistakes-10135080

## ♥
Gotta try this on next project ;) [Unicode CSS classes](http://davidwalsh.name/unicode-css-classes)

# Web page performance
- http://csswizardry.com/2013/01/front-end-performance-for-web-designers-and-front-end-developers/

## Images and CSS sprites
Use http://www.smushit.com/ysmush.it/ to sompress used images.

Use spriting in order to cut down number of HTTP requests. Avoid empty pixels.
*"if you can’t sprite an element because it’s fluid, you place an empty element inside it that you can fix the dimensions of that you then can sprite up"* (csswizardry article on performance)
```html
<a href="#"><i class="icon  icon--balicky"></i> Balicky</a>
```

CSS sprites caveats solutions on [Smashing magazine](http://coding.smashingmagazine.com/2012/04/11/css-sprites-revisited/) (04/2012).

## Check the page performance and refine
Use tools to check on performance during development and especially before going to production.
- https://developers.google.com/speed/pagespeed/
- http://yslow.org/

# Responsive must
//TODO
- viewport?

#QA
ST 2 plugins: JSHint (http://jshint.com), SublimeLinter (https://github.com/SublimeLinter/SublimeLinter-for-ST2)

#WordPress development workflow
Local development (XAMPP, SublimeText2, sometimes Stylus+Prepros, git repo) -> git push theme files to dev server (actually test server), push database with [WP Migrate DB Pro](https://deliciousbrains.com/wp-migrate-db-pro/) -> deploy to production with *(to be decided - deployhq?)*

#Patterns
- sticky footer:
http://www.cssstickyfooter.com/using-sticky-footer-code.html
ryanfait.com/resources/footer-stick-to-bottom-of-page/ - with extra push element
http://philipwalton.github.io/solved-by-flexbox/demos/sticky-footer/ - with flexbox

- site logo
Site logo is content, mark it up like content (do not use background-image). Avoid using h1 as logo. (http://csswizardry.com/2010/10/your-logo-is-an-image-not-a-h1/)
- http://gandrweb.com/blog/comments/semantically-correct-website-logos

- styling searchbox

#Other

## Social media
- use og
- use twittercards

#Links
- https://github.com/Snugug/north - a much more complex project guide
- http://www.welcomebrand.co.uk/thoughts/the-big-list-of-design-and-development-resources/
- https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills
- http://mdo.github.io/code-guide/
- http://cssguidelin.es/



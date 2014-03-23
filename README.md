mantra.am
=========

Read. Code. Write. Repeat.

List of personal front-end best practice.

**Content**

- my CSS conventions
  - BEM
  - js-delimited classes
  - OOCSS
  - CSS Code smell 
- Web page performance
- Responsive must
- QA
- WordPress workflow
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

# Web page performance
- http://csswizardry.com/2013/01/front-end-performance-for-web-designers-and-front-end-developers/

## Images
Use http://www.smushit.com/ysmush.it/

## Check the page performance and refine
- https://developers.google.com/speed/pagespeed/
- http://yslow.org/

# Responsive must
//TODO
- viewport?

#QA
ST 2 plugins: JSHint (http://jshint.com), SublimeLinter (https://github.com/SublimeLinter/SublimeLinter-for-ST2)

#WordPress development workflow
Local development (XAMPP, SublimeText2, sometimes Stylus+Prepros, git repo) -> git push theme files to dev server (actually test server), push database with [WP Migrate DB Pro](https://deliciousbrains.com/wp-migrate-db-pro/) -> deploy to production with *(to be decided - deployhq?)*

#Other

## Social media
- use og
- use twittercards

#Links
- https://github.com/Snugug/north - a much more complex project guide
- http://www.welcomebrand.co.uk/thoughts/the-big-list-of-design-and-development-resources/
- https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills



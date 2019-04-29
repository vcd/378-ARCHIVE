# Midterm

## 0. Overview
* 1st Hour: Work Independantly. Open book, open Internet, but no communicating with another human-being. 
* 2nd Hour: Pair Programming within groups communicating and learning from other human beings. 

## 1. Dev Tools

* [Recreate screenshot as closely as possible](https://s3-us-west-2.amazonaws.com/s.cdpn.io/16425/midterm-devtools.png)
* Using Google Chrome, Go to [Google.com](https://google.com)
* Open _Developer Tools_
* Change content above search bar to this image. Hint, right/ctrl-click, then "Edit as HTML": 

```html
<img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/16425/ewulogo.png" />
```
* Change `body` background, to this image:

```css
background-image: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/16425/ewu-orientation.jpg);
background-repeat: no-repeat;
background-size: cover;
```

* For Search Bar, change `border-radius` to `0` 

```css
border-radius: 0;
```

* Take a screenshot

## 2. Framework & Process

* [Recreate to this screenshot as closely as possible](https://s3-us-west-2.amazonaws.com/s.cdpn.io/16425/lettering-midterm.png)
* _Download_. Do not _clone_ our Web 2 Framework from [https://github.com/ewuweblab/web-2-framework](https://github.com/ewuweblab/web-2-framework)
* Change name of repo (downloaded folder) to `midterm`
* Open in VS Code and run _Live Server_ extension for _Local Staging Server_
* Open `index.html`, add content to `body` element

```html
<h1>Midterm</h1>
```
* Continue editing `index.html` and add **jQuery plugin** in correct order-of-execution

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/lettering.js/0.7.0/jquery.lettering.min.js"></script> 
```
* Open `styles.css`, add this content: 

```css
h1 {
  text-align: center;
  text-transform: uppercase;
}

h1 span:nth-child(even) {
  color: gray;
}

h1 span:nth-child(odd) {
  color: red;
}
```

* Open `scripts.js`, add: 

```js
$('h1').lettering();
```

* If, the letters of the word "Midterm" alternate red/gray, then continue. Publish to GitHub i.e. the _Remote Production Server_
* Publish repo by enabling _GitHub Pages_ for this repository 
* Check that URLs for both _Backend_ and _Front-end_ are working. 
    - Backend i.e. the source files
    - Front-end i.e the result of the files

## 3. Abstraction with Markdown

* [:black_nib: Fork this Pen](https://codepen.io/manikoth/pen/ROdqbg)
* [Recreate as closely as possible per this screenshot](https://s3-us-west-2.amazonaws.com/s.cdpn.io/16425/markdown-syntax-blockquote.png)
* Using Markdown syntax to compile to HTML `<blockquote>`
  * REF: https://guides.github.com/features/mastering-markdown
* Convert left quote, right quote, and ampersand to character entities
  * REF: http://smartquotesforsmartpeople.com
* Add Playfair Font from Google Fonts: 
 * REF: https://www.google.com/fonts#UsePlace:use/Collection:Playfair+Display
* Apply Playfair Display font to `<blockquote>`

## 4. Positioning

* [:black_nib: Fork this Pen](https://codepen.io/manikoth/pen/PgLxNR)
* [Recreate as closely as possible per this screenshot](https://s3-us-west-2.amazonaws.com/s.cdpn.io/16425/midterm-positioning.png)
 * Add 60px border radius to each social media image
 * Absolutely position icons in lower corner
      - right: -10px;
      - bottom: -10px; 

## 5. SVG

* [:black_nib: Fork this pen](https://codepen.io/manikoth/pen/XQGyeX)
* [Recreate as closely as possible per this screenshot](https://s3-us-west-2.amazonaws.com/s.cdpn.io/16425/svg-midterm.png)
* Get this [SVG icon](https://iconmonstr.com/color-fan-2-svg/) from Icon Monster
    * https://iconmonstr.com/color-fan-2-svg/
* Optimize icon with [SVG OMG tool](https://jakearchibald.github.io/svgomg)
    * https://jakearchibald.github.io/svgomg/
* Scale up SVG 12x (twelve times) it's size
    * REF: https://cssreference.io/property/transform/
* Color svg to `aquamarine`
    * REF: https://css-tricks.com/almanac/properties/f/fill/

## 6. Q&A

* [Complete the following Midterm Survey](https://airtable.com/shrVnyFGfsfrRq2jc) at https://airtable.com/shrVnyFGfsfrRq2jc


<!-- ## CSS Transitions
## JavaScript -->


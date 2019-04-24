# _Atomic Design_ Components

> [Collection of all Google Doodle CodePen pens][1]

# The Setup

## Setting the Stage
Blank Google Doodle template. A "stage" for the animations. 

* Pen: [Google Doodle Stage][2]

## Doodle Content
Pros: Content, like another other text, image, svg loaded with `img` element. Can be used for background images. No code, few features.

Cons: Limitations of image format. Can only change certain properties with animations. Lots of code, many features.  

* Pen: [Doodle Content][3]

## SVG as Code
Opposite of SVG as Images. Use Illustrator to make SVGs as code. 

* Pen: [SVG as Code][4]
* REF: Not all SVG properties available yet, refer to [SVG properties via CSS][5]. See `fill` and `stroke` properties

## Initial Positioning of Elements
Use `position` properties to set initial positioning before Box Model, transforms, or animations are applied.  

* Pen: [Initial Positioning of Elements][6]

---- 
# The Events

## Pseudo Classes on SVG
`:link`, `:visited`, `:hover`, `:focus`, `:active` pseudo classes work the same on SVGs, as any element. 

* Pen: [Pseudo Classes on SVGs][7]

## Trigger Child with Parent
Hover over parent `#stage` ID, then apply pseudo classes on child elements. 

* Pen: [Trigger Child with Parent][8]

## `click` and `toggleClass` methods
Use jQuery’s `click` to and `toggleClass` methods for additional control of events. 

* Pen: [`click` event]()
* Pen: [`toggleClass` method]()
* Pen: [Toggle Class on Click]()

---- 
# The Animations

## Transitions on Pseudo Classes
CSS `transition` properties can be applied to any property with a numerical value. 

* Do it manually first. 
* What is the first frame? What is the last frame? 
* Pen: [CSS Transitions on Pseudo Classes][12]

## 2D Transforms
Most 2D transforms can be applied to SVG elements. 

* Use `transform` property, `translate` functions to move elements around stage
* REF: TreeHouse CSS Transforms
* Pen: [CSS Transforms on SVGs][13]

## Animate with Keyframe Animation 
More control with more frames of animation. 

 * Get standard UI animations form [Animate.css][14]
* Or [many of examples from CodePen][15]

## CSS Animation Stroke Dash on Paths
Pro: No JavaScript needed. Con: Sometimes JavaScript is needed for this. 

* Pen: [Marching Ants][16]
* Pen: [Animation on Stroke/Line Paths][17]

## Random Generator
Randomization adds an [emotional component to animation. See example card game][18] 

* Pen: [Random Number Generator][19]
* Pen: [Random Text][20]
* Pen: [Random Emoji][21]. Remember, it’s all text.
* Pen: [Random Background Image][22]
* Pen: [Random Background Color with `addClass()`][23]
* Pen: [Random Image with `attr()` and JS Arrays][24]





[1]:	http://codepen.io/collection/Xgwdmx/
[2]:	http://codepen.io/manikoth/pen/evpozv
[3]:	http://codepen.io/manikoth/pen/yMYrVa
[4]:	http://codepen.io/manikoth/pen/EWVJNw
[5]:	http://www.opera.com/docs/specs/presto25/svg/cssproperties/
[6]:	http://codepen.io/manikoth/pen/MpaxMy
[7]:	http://codepen.io/manikoth/pen/yMYrvM
[8]:	http://codepen.io/manikoth/pen/mWegGN
[12]:	http://codepen.io/manikoth/pen/PpPgXq
[13]:	http://codepen.io/manikoth/pen/MpKyLz
[14]:	https://daneden.github.io/animate.css/
[15]:	http://codepen.io/search/pens?q=animation&limit=all&type=type-pens
[16]:	https://codepen.io/manikoth/pen/mvgrVd?editors=1100
[17]:	https://codepen.io/manikoth/pen/BYrEZX
[18]:	https://codepen.io/manikoth/pen/mtGCD?editors=1010
[19]:	https://codepen.io/manikoth/pen/eZjzgB?editors=0110
[20]:	https://codepen.io/manikoth/pen/GZXYzM
[21]:	https://codepen.io/manikoth/pen/reRMgx
[22]:	https://codepen.io/manikoth/pen/QGKjwx
[23]:	https://codepen.io/manikoth/pen/xZmrqz?editors=0110
[24]:	https://codepen.io/manikoth/pen/LvwFa?editors=1010
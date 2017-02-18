# angularjs-slideshow
A light and simple slide show with native angularjs without any external plugin.

![angularjs slidesho](http://tanabche.com/wp-content/uploads/2017/02/angular-slideshow.jpg)

The lightest and simplest slideshow with angularjs under 2 min. There is no need to add external plugin.

## Demo
http://codepen.io/thinkdiff/pen/xgNyRz

## Speed
I haven't use any external plugin for angular and this is just native code. It has't more request for your project and it's too fast and flexible. you can add all of your images as much as you want.

## Usage
Everything that you should do is put your images address in an array like this:
```
var slides = [
    	{'img' : 'http://tanabche.com/wp-content/uploads/2017/02/1.jpg'},
    	{'img' : 'http://tanabche.com/wp-content/uploads/2017/02/2.jpg'},
    	{'img' : 'http://tanabche.com/wp-content/uploads/2017/02/3.jpg'},
    	{'img' : 'http://tanabche.com/wp-content/uploads/2017/02/4.jpg'},
    	{'img' : 'http://tanabche.com/wp-content/uploads/2017/02/5.jpg'},
    	{'img' : 'http://tanabche.com/wp-content/uploads/2017/02/6.jpg'},
];
```

## Slides Effect
There is 3 type of effect for this slideshow:
```
- fadeIn
- fadeInLeft
- fadeInRight
```
Yout just need to change it here: `<img class="slide animated fadeIn"...`
And for more effect you can add other styles in https://daneden.github.io/animate.css/

#### For changing speed of slides just change `setInterval` function speed:
```
},4000);
```
- each 1000 equal 1 second.

## Styles
There is style in `css/style.css` and you can change styles of slider by inspector in your fvorit browser.

## Support And Help:
#### Website : http://pourhasan.ir
#### Email   : asp.2073@gmail.com


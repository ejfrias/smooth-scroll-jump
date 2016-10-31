# smooth-scroll-jump
A lightweight, easy, straight-forward and very simple smooth scrolling link jumper made with jQuery


### Demo
[http://ejfrias.com/playground/smooth-scroll-jump](http://ejfrias.com/playground/smooth-scroll-jump)


### Requirement
jQuery 1.x and above


### How to use
Just add the script before your closing `</body>` tag:
```
<script src="/path/to/smooth-scroll-jump.js"></script>
```

**That's it!** You can now add the smooth scrolling jumper to a link by using `smooth-scroll-jump` attribute
```
<a href="#content" smooth-scroll-jump>Go to content</a>
```


### Options
All options are required to be prefixed with `jump-`

Name | Type | Default | Description
---- | ---- | ------- | -----------
animate | boolean | true | Jumping animation which will show the smooth scrolling effect.
speed | integer | 500 | Animation speed to milliseconds. Setting `animate` option to false will render `speed` to 0.
distance | integer | 20 | Distance of the target element from the top of the screen in pixels.
target-attr | string | id | If you prefer using `name` or other attribute than `id`.
change-hash | boolean | false | Decides if the hash in the location bar should be updated.
header | string | (empty) | Selector of the header element. By class, id, attribute, element node, etc. Scroll distance will be recalculated if the header has a fixed position.


### Contributing
Since this plugin was made to be as simple as possible, requesting and/or proposing a feature would not be entertained. However, submitting bugs/issues are always welcome.
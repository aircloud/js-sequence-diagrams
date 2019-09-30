## JS Sequence Diagrams 

**[Playground](http://niexiaotao.cn/sequence/)**

Origin repo and doc： [There](https://github.com/bramp/js-sequence-diagrams)

Add Features:

* can define svg attributes for action
* can download png directly
* Optimized the layout of the experience page

### svg attributes usage

We can use JSON String to define style, for example: 

```
Andrew->Andrew: Says Hello `{"stroke":"#ff0000", "fill":"#ff0000"}`
```

Then this signal's color will be red.

In addition, for convenience, we have defined an alias type `color`. So the above can also be written like this:

```
Andrew->Andrew: Says Hello `{"color":"#ff0000"}`
```



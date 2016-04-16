# prefixer-sass
add prefix your css

## Using

Download
```
// Import
@import "prefixer";
```

```
// Mixin Call
@include prefixer(transform, scale(1.2))
```

```
// Then Return
 transform : scale(1.2);
 -webkit-transform : scale(1.2);
 -moz-transform : scale(1.2);
 -ms-transform : scale(1.2);
 -o-transform : scale(1.2);
```

## Supported
* .animation(@args)
* .background-size(@args)
* .border-radius(@args)
* .box-shadow(@args)
    * .inner-shadow(@args) 
* .box-sizing(@args)
* .columns(@args)
* .gradient(@default,@start,@stop) 
* .keyframes(@name; @args)
* .opacity(@factor)
* .transform(@args)
* .text-shadow(@args)
* .transition(@args)
* (fuckin) FLEX


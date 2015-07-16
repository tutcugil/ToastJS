# ToastJS
Toast message Javascript library

# How to use

1 - Add <b>jquery.toast.js</b> to your project (requires jquery)<br>
2 - Done! Show toast messages! that simple

```javascript
Toast.show("This is a <b>Toast</b> message on bottom"); 
```

# Customize it

You can show custom toast messages with <b>ToastJs</b><br>
- Change foreground or background colors of toast<br>
- Change position or alignment<br>
- Change duration of animations<br>
- Change font size, opacity etc<br>

Some customization examples <br>

```javascript
Toast.show({
    message  : "This is a <b>Toast</b> message on top",
    position : Toast.POSITION_TOP 
}); 
```

```javascript
Toast.show({
    message  : "This is a long <b>Toast</b> message on bottom",
    duration : Toast.DURATION_LONG 
});  
```

```javascript
Toast.show({
    message    : "This is a custom <b>Toast</b> message on bottom with purple background",
    background : "#630460" 
});  
```

```javascript
Toast.show({
    message    : "This is a custom <b>Toast</b> message on top right with blue background",
    background : "#004a80",
    position   : Toast.POSITION_TOP,
    align      : Toast.ALIGN_RIGHT
});  
```

You can show multiple toast messages <b>ToastJS</b> will queue them and show in order

These are default parameters of Toast
```javascript
position    : Toast.POSITION_BOTTOM,
duration    : Toast.DURATION_NORMAL,
align       : Toast.ALIGN_CENTER,
class       : Toast.DEFAULT_CLASS,
background  : '#000000',
color       : '#ffffff',
opacity     : '0.6',
radius      : '16',
fontSize    : '14px',
appearTime  : 0.3, // seconds
message     : '',
top         : '40px', // if position-top top:40px, position-bottom bottom:40px
left        : '40px' // if align-left left:40px, align-right left:40px
```

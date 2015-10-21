k-textarea
==========

Expanding textarea for KanteleJS

http://alistapart.com/article/expanding-text-areas-made-elegant/

##Demo

https://derby-demos.herokuapp.com/d-textarea

## How to use

```javascript
app.component(require('k-textarea'));
```

```html
<view name="k-textarea" text="{{#root._page.text}}"></view>
```

Or 

```javascript
app.component(require('k-textarea'));
```

```html
<view name="d-textarea" id="my-textarea" name_="myform[text]" placeholder="Enter text..." class="my-class" on-keydown="textareaKeyhandler()" text="{{#root._page.text}}"></view>
```

```javascript
app.proto.textareaKeyhandler = function(event, element) { /* do something */}
```


## style.css

Needs to be imported from the main app now. In styles/app/index.styl:

```css
@import '../../node_modules/d-textarea/style.css'
```

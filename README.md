# markdown_highlight.js

markdown_highlight.js markdown and highlight any text include code on web page, it base [marked](https://github.com/chjj/marked) and [highlight.js](https://github.com/isagalaev/highlight.js)

## Usage

```html
<link rel="stylesheet" title="Default" href="styles/default.css">
<script src="markdown_highlight.js"></script>
<script>
$(document).ready(function(){
  var markdownString = 'I am using __markdown__.\n```js\n alert("hello"); \n```';
  $("#blog_preview").html(marked(markdownString));
});
</script>

<div id="blog_preview">
</div>

```

## Sample
Just clone the code and open `test.html` can see the test sample
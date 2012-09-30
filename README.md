# Live.js

[Live.js](http://livejs.com/) is a JavaScript written by [Martin Kool](http://twitter.com/mrtnkl) to autoreload the page when an included script source ( CSS, JS or HTML itself ) is updated.

I forked their version because I couldn't find the source code hosted anywhere to integrate some bug fixes.

## Sample usage

Include live.js file to monitor html, js and css changes.

```html
<script type="text/javascript" src="live.js"></script>
```

Include live.js#css to monitor css changes only.

```html
<script type="text/javascript" src="live.js#css"></script>
```

Include live.js#js to monitor js changes only.

```html
<script type="text/javascript" src="live.js#js"></script>
```

Include live.js#html to monitor html changes only.

```html
<script type="text/javascript" src="live.js#html"></script>
```

Mix and match to monitor a preferred combination such as live.js#html,css.

```html
<script type="text/javascript" src="live.js#html,css"></script>
```

## License

Was originally licensed under the MIT License.
Licensed under the MIT License. See LICENSE for details.

Copyright © 2011 by Martin Kool and Q42
Copyright © 2012 Edoardo Tenani

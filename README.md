<h1>ESP8266 - 128x64 OLED Wiring</h1>

<h2>Aim</h2>
Get a 128x64 OLED Module working with a clone of the WeMos D1 Mini.

<h2>Parts</h2>
<ul>
 <li>WeMoS D1 Mini Clone (purchase on Aliexpress marked as "Mini ESP8266")<BR><img src="./resources/MiniESP8266-Front.jpg" width="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./resources/MiniESP8266-Back.jpg" width="200"><br><i><b>Note:</b> The "SCK" Pin maps to I2C "SCL"<br><br></i>
<li>OLED Module (purchase on Aliexpress marked as "GM009605")
<BR><img src="https://github.com/asleepatwork/esp8266-oled-gm009605/raw/master/resources/OLED128x64-GM009605-Front.jpg" width="200">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./resources/OLED128x64-GM009605-Back.jpg" width="200"><br><b>Note:</b> <i>The "SCK" Pin maps to I2C "SCL"</i><i>The "SCK" Pin maps to I2C "SCL"<br><br></i>
<li>2x 10k Ohm 5% Resistors as Pull Up</li></ul>

Basic useful feature list:

 * Ctrl+S / Cmd+S to save the file
 * Ctrl+Shift+S / Cmd+Shift+S to choose to save as Markdown or HTML
 * Drag and drop a file into here to load it
 * File contents are saved in the URL so you can share files

<img src="https://github.com/asleepatwork/esp8266-oled-gm009605/raw/master/resources/OLED_128x64_i2c%20Breadboard%20View1.png" width="600">


I'm no good at writing sample / filler text, so go write something yourself.

Look, a list!

 * foo
 * bar
 * baz

And here's some code! :+1:

```javascript
$(function(){
  $('div').html('I am a div.');
});
```

This is [on GitHub](https://github.com/jbt/markdown-editor) so let me know if I've b0rked it somewhere.


Props to Mr. Doob and his [code editor](http://mrdoob.com/projects/code-editor/), from which
the inspiration to this, and some handy implementation hints, came.

### Stuff used to make this:

 * [markdown-it](https://github.com/markdown-it/markdown-it) for Markdown parsing
 * [CodeMirror](http://codemirror.net/) for the awesome syntax-highlighted editor
 * [highlight.js](http://softwaremaniacs.org/soft/highlight/en/) for syntax highlighting in output code blocks
 * [js-deflate](https://github.com/dankogai/js-deflate) for gzipping of data to make it fit in URLs

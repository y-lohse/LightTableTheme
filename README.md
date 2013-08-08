# Light Table theme for CodeMirror / Brackets

A theme for [CodeMirror](http://codemirror.net/) based on the [Light Table](http://www.lighttable.com/) editor default theme. Designed for [brackets](https://github.com/adobe/brackets) but should work with any CodeMirror instance.

[![Some css](http://yannick-lohse.fr/assets/2013/08/css.png](http://yannick-lohse.fr/assets/2013/08/css.png)
[![Some js](http://yannick-lohse.fr/assets/2013/08/js.png](http://yannick-lohse.fr/assets/2013/08/js.png)

# Improved readability

Well balanced contrast ensures the code is very readable. I have bad eye sight, I know what I'm talking about.

Oh, it's also pretty.

# Current line highlighting

The current line you're working on is highlighted, so you'll find the exact spot you were at when you come back from another app.

# Discret scrollbars

How often are you clicking on the scrollbars? I guess never.

With this theme they are reduced to the minimum; they'll effectively show you where you are in your code compared to the file size, but otherwise they won't call for attention.

# Bottom padding

Content should never be glued to the bottom of your screen, that's just impractical. This theme provides some padding for better comfort.

![Padding at th bottom](http://yannick-lohse.fr/assets/2013/08/bottom.png)

## Fabrication secrets

[I wrote a quick note about it on my blog.](http://yannick-lohse.fr/2013/08/08/A-better-CodeMirror-theme.html)
It's mostly written for hml, css and js. Other language support should work but might not be throughout.

## Known (minor) issues

- The width of the line number is fixed, so very long line numbers may be a bit hidden. But 5 digits are not a problem, and if your file has more than 99 999 lines I think you have more important issues at hand.
- At least in Brackets, the custom scrollbars only kick in after the code frame has changed once (opening another file or anything like that). I don't know how to fix it right now but I've never noticed it, and I use this theme every day.

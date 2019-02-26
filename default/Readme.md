The default style for Darktable 2.6
===


Installation
==
1. Copy darktable.css to your Darktable config directory
1. Start Darktable

Using with override files
==

Some style files only override certain values.
In that case you need darktable.css with the below line at the end:
```css
@import "custom.css";
```
and place the other style in custom.css file in the same directory.
```shell
$ pwd
/Users/username/.config/darktable
$ ls -1 *.css 
custom.css
darktable.css
$
```
---
layout: default
title: Typesetting Guide
description: Basics to typesetting with examples
---

[• back](./) [• Timing guide](./timing-guide.html)

## Table of contents 

1. [Useful sites](#useful-sites)
2. [Level 1: Basic tags](#level-1-basic-tags)
3. [Level 2: Transformations](#level-2-transformations)
4. [Recommended scripts](#recommended-scripts)

## Useful sites

[Aegisub tags](http://docs.aegisub.org/3.2/ASS_Tags/)
Official documentation for all available tags in Aegisub, e.g. \fad, \t

[Typesetting guide](https://unanimated.github.io/ts/index.htm)
Focused on typesetting for anime, also with some really useful scripts

[top](#table-of-contents)

---

## Level 1: Basic tags

- [Colors](#colors)
- [Border, shadow, bold, italic, fonts](#border-shadow-bold-italic-fonts)
- [Size](#size)
- [Position](#position)
- [Blur](#blur)
- [Line breaks and spacing](#line-breaks-and-spacing)
- [Fade in and out](#fade-in-and-out)
- [Opacity](#opacity)
- [Clipping](#clipping)
- [Movement](#movement)
- [Reset everything](#reset-everything)

[top](#table-of-contents)

### Colors

![](./images/t_color.png)

`{\c&H000000&}This is {\c&H260EC8&}a text`

You can change the color of the text with following tags:

- \c - Main color
- \3c - Border color
- \4c - Shadow color

Or these buttons:

![](./images/t_color_buttons.png)

A window opens where you can select a color (use the pipette symbol to pick a color from the video):

![](./images/t_color_picker.png)

Tip: Quickly change to white in the editor by typing *\c*

[Level 1: Basic tags](#level-1-basic-tags)

### Border, shadow, bold, italic, fonts

#### Border

![](./images/t_border.png)

`{\bord4}This is a text`

There's also `\xbord`and `\ybord` for further manipulation.

#### Shadow

![](./images/t_shadow.png)

`{\shad4}This is a text`

There's also `\xshad`and `\yshad` for further manipulation.

#### Bold, italic, underlined

![](./images/t_bold_italic.png)

`{\b1}This is a bold text {\b0\i1} and italic {\i0\u1} and underlined`

#### Font

![](./images/t_font.png)

`This was Candara {\fnArial} and now it's Arial`

[Level 1: Basic tags](#level-1-basic-tags)

### Size

![](./images/t_fs.png)

`{\fs30}Small text {\fs100}big text`

![](./images/t_fsc.png)

`{\fscx150}Wide text {\fscy200}Tall text`

Or this button for `\fscx` `\fscy`:

![](./images/t_fsc_button.png)

100 is the default size for `\fscx` `\fscy`

[Level 1: Basic tags](#level-1-basic-tags)

### Position

`{\pos(412.322,286)}This is a text`

Or this button:

![](./images/t_pos.png)

A little box appears next to the text which you can drag to change its position:

![](./images/t_pos_drag.png)

You can also anchor the text to different video positions by using `\an` and the numbers 1 - 9:

![](./images/t_an.png)

[Level 1: Basic tags](#level-1-basic-tags)

### Blur

![](./images/t_blur.png)

`{\shad4\bord4}normal {\blur10}everything {\blur0\be10}or just the edges`

[Level 1: Basic tags](#level-1-basic-tags)

### Line breaks and spacing

![](./images/t_break.png)

`I break\Nthis\h\h\h\hwith spaces {\fsp10}and wider`

- `\N` Line break, in the editor press *SHIFT + ENTER* to add a line break at cursor position
- `\h` Hard space, very useful in combination with `\an` and `\N` to avoid splitting a line in two
- `\fsp` Space between letters, default is 1
- `\q` Mode for line wrapping, `\q2` is no automatic line wrapping

[Level 1: Basic tags](#level-1-basic-tags)

### Fade in and out

`{\fad(300,300)} This text fades in for 300ms and out for 300ms`

First number is fade-in time, second one is fade-out time

**Q. How to I get precise fade times?**

Below the video player there are these numbers:

![](./images/t_fade.png)

Select your line and jump with the video to the frame where the caption is fully seen. The + number (left) is your fade-in time. For fade out, jump to the one frame before the caption starts to fade out. The - number (right) is your fade-out time.

[Level 1: Basic tags](#level-1-basic-tags)

### Opacity

[Level 1: Basic tags](#level-1-basic-tags)

### Clipping

[Level 1: Basic tags](#level-1-basic-tags)

### Movement

[Level 1: Basic tags](#level-1-basic-tags)

### Reset everything

![](./images/t_reset.png)

`{\c&HCD302A&\fs60\shad2\bord2\blur2}Very fancy text {\r}and now it's normal`

`\r` resets everything to the default settings of the style

[Level 1: Basic tags](#level-1-basic-tags)


---

## Level 2: Transformations

[top](#table-of-contents)

![](./images/t_fade.png)

TODO desc

### Text grows / shrinks

[Level 2: Transformations](#level-2-transformations)

### Text changes color

[Level 2: Transformations](#level-2-transformations)

### Text appears from left to right / right to left

[Level 2: Transformations](#level-2-transformations)

### Box with text

[Level 2: Transformations](#level-2-transformations)

---

## Recommended scripts

[top](#table-of-contents)
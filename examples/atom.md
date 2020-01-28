# RTL and BiDi Display
`- Basic mixed-direction text like this الكلمة seems to display correctly.`
 - Basic mixed-direction text like this الكلمة seems to display correctly.

# Alignment
 - There seems to be no way to set the base text-direction or even align text to the right.
 - The beginning of the line is always on the left and the end of the line is always on the right, regardless of the direction of the text in the line.

# Cursor
 - The cursor cannot be positioned with the mouse or arrow keys inside RTL text, only at the beginning or end of it.

# Selecting Text
 - Double-clicking on a word to select it highlights a different word or area of the screen and selects a different word than the one clicked.
`هذه الكلمة`
    - Double-clicking on هذه and pressing CMD+C copies الكلمة.
    - Double-clicking on الكلمة and pressing CMD+C copies هذه.
 - There is no way to visually select characters within a word, since dragging the cursor either does nothing or selects the entire word.
 - You can select individual characters by going to the left or right side of the RTL text, holding Shift, and pressing the arrow key in the opposite direction (left or right), but this selects the character(s) on the opposite side of the RTL text.

# Markup
 - Element names in angle brackets seem to work as long as the element names and element content is all LTR or RTL.
```
<code>هذه الكلمة</code>
<رمز>الكلمة</رمز> <رمز>هذه الكلمة</رمز>
```
 - However the code is difficult to type because the angle brackets at the beginning or end of the line reverse orientation and move to the other side of the line unless the end tag is present on the same line. This is also a problem when the element content spans across lines. Lines 2-3 below have the same content as line 1, but with break between the words هذه and
```
 الكلمة
<رمز>هذه الكلمة</رمز>
<رمز>هذه
 الكلمة</رمز>
 ```
 - Here lines 2-3 below are the same as line 1, but with a break between the element and attribute name.
```
<رمز كتاب="ابجد">هذه الكلمة</رمز>
<رمز
كتاب="ابجد">هذه الكلمة</رمز>
```

# Markdown
 - Markdown text seems to be recognized correctly, beginning-of-line symbols are placed on the left.
 ```
 ## مرحبا
  - ا
   - ب
    - ت
```
## مرحبا
 - ا
  - ب
   - ت
 - If one can overcome the challenges of correctly orienting brackets and navigating the cursor, Markdown links can be entered and display correctly, except that the URL is to the right of (i.e., before) the linked text.
`[رابط تشعبي](https://ar.wikipedia.org/wiki/رابط_تشعبي)`
[رابط تشعبي](https://ar.wikipedia.org/wiki/رابط_تشعبي)

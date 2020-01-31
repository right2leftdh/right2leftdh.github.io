---
name: Test Right-to-Left Text
about: Complete this checklist to test right-to-left and multidirectional text handling
  in an app or a text field on a website.
title: "[App or website name] right-to-left test"
labels: in triage
assignees: nathangibson

---

# Name of app/URL of website
What app or website are you testing?
Are you testing a particular field or type of document?

# Desktop (please complete the following information):

    OS: [e.g. iOS]
    Browser [e.g. chrome, safari]
    Version of app or website (if applicable) [e.g. 22]

# Smartphone (please complete the following information):

    Device: [e.g. iPhone6]
    OS: [e.g. iOS8.1]
    Browser [e.g. stock browser, safari]
    Version of app or website (if applicable) [e.g. 22]

TESTS FOR PLAIN TEXT EDITORS
============================
Copy this text into your text editor, answer the questions, and then paste it back here. Put an x inside the [] to answer the questions below. Feel free to add screenshots in the issue.

TEXT DISPLAY
============
1. Does basic mixed-direction text display correctly? The first line should display the numbers left-to-right, the second line right-to-left.
Word 1, 2 الكلمة, word 3
كلمة 1، word 2, كلمة 3

-[] Yes
If No, what happened?

LINE DIRECTION
==============
2. Can you set the base text-direction in the program's menu? Try setting the direction of the line below as right-to-left. The period should be on the left side of the line.
هذه الكلمة.

-[] Yes
If No, what happened?

3. Can you align text to the right (either using paragraph alignment or by setting the text direction)?
هذه الكلمة.

-[] Yes
If No, what happened?

4. Does the beginning of the line start on the right for RTL text? (Try entering a line break with the cursor on the right side.)
هذه الكلمة.

-[] Yes
If No, what happened?

SELECTING TEXT
==============
5. Can you position the cursor correctly in RTL text with the mouse?
هذه الكلمة.

-[] Yes
If No, what happened?

6. Can you position the cursor correctly in RTL text with the arrow keys?
هذه الكلمة.

-[] Yes
If No, what happened?

7. If you double-click on a word in RTL text, does it highlight the correct word?
هذه الكلمة.

-[] Yes
If No, what happened?

8. If you double-click on a word in RTL text, does it select the correct word? (Test by copying the word to the clipboard and pasting it somewhere else.)
هذه الكلمة.

-[] Yes
If No, what happened?

9. Can you select characters within an RTL word using the mouse?
هذه الكلمة.

-[] Yes
If No, what happened?

10. Can you select characters within an RTL word using the keyboard?
هذه الكلمة.

-[] Yes
If No, what happened?

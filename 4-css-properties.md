# CSS Properties

**Content**

1\. CSS animation Property

2\. CSS background-color Property

3\. CSS background-attachment Property

4\. CSS border Property

5\. CSS border-width Property

6\. CSS color Property

7\. CSS column-count Property

8\. CSS column-gap Property

9\. CSS direction Property

10\. CSS filter Property

11\. CSS font-size Property

12\. CSS font-style Property

13\. CSS font-variant Property

14\. CSS gap Property

15\. CSS margin Property

16\. CSS padding Property

17\. CSS scroll-behavior Property

18\. CSS table-layout Property

19\. CSS text-align Property

20\. CSS text-decoration-color Property

21\. CSS text-decoration-style Property

22\. CSS white-space Property

23\. CSS word-spacing Property

24\. CSS word-wrap Property

25\. CSS writing-mode Property

26\. References

# 1. CSS animation Property

**Example**

-   Binding an animation to a \<div\> element, using the shorthand property:

div {  
animation: mymove 5s infinite;  
}

**Output**

![](media/448d4cbbd9aca07e5e4e6630fa3045bf.png)

# 2. CSS background-color Property

**Example**

-   Set the background color for a page:

body {background-color: coral;}

**Output**

**![](media/ed32131a8ea0d1f40f583a08513eed59.png)**

# 3. CSS background-attachment Property

**Example**

-   A background-image that will not scroll with the page (fixed):

body {  
background-image: url("img_tree.gif");  
background-repeat: no-repeat;  
background-attachment: fixed;  
}

**Output**

![](media/6cd5d6189548ce34e772ae1999db68d7.png)

# 4. CSS border Property

**Example**

-   Set the style of the borders for different elements:

h1 {  
border: 5px solid red;  
}

h2 {  
border: 4px dotted blue;  
}

div {  
border: double;  
}

**Output**

**![](media/64225c7ca06c758f9dc70eabf94e4be2.png)**

# 5. CSS border-width Property

**Example**

-   Set a width for the borders:

div {border-width: thin;}

**Output**

![](media/4a7c9ba48c31ba0cfdf037dc4b9fe82e.png)

# 6. CSS color Property

**Example**

-   Set the text-color for different elements:

body {  
color: red;  
}

h1 {  
color: \#00ff00;  
}

p.ex {  
color: rgb(0,0,255);  
}

**Output**

![](media/9be872ad274086d247586b9f2c5e4fb4.png)

# 7. CSS column-count Property

**Example**

-   Divide the text in the \<div\> element into three columns:

div {  
column-count: 3;  
}

**Output**

![](media/6993db0188e34c770c9fad0e1c0125f1.png)

# 8. CSS column-gap Property

**Example**

-   Specify a 40 pixels gap between the columns:

div {  
column-gap: 40px;  
}

**Output**

**![](media/997fd5ab20b0e9a3c7b624a8cb8ac4a2.png)**

# 9. CSS direction Property

**Example**

-   Set the text direction to "right-to-left":

p.rtl {  
direction: rtl;  
}

**Output**

**![](media/79369b6732260eaa6f02b5ee9efddb57.png)**

# 10. CSS filter Property

**Example**

-   Change all images to black and white (100% gray):

img {  
filter: grayscale(100%);  
}

**Output**

![](media/fc06b02f9e59e005aa3fa63faff60490.png)

# 11. CSS font-size Property

**Example**

-   Set the font size for different elements:

div.a {  
font-size: 15px;  
}

div.b {  
font-size: large;  
}

div.c {  
font-size: 150%;  
}

**Output**

![](media/1417f38f6758a55b840c95c0f9303140.png)

# 12. CSS font-style Property

**Example**

-   Set different font styles for three paragraphs:

p.a {  
font-style: normal;  
}

p.b {  
font-style: italic;  
}

p.c {  
font-style: oblique;  
}

**Output**

![](media/f30e1ee863545b20a8c26c04ca122da0.png)

# 13. CSS font-variant Property

**Example**

-   Set a paragraph to a small-caps font:

p.small {  
font-variant: small-caps;  
}

**Output**

![](media/fc6d0c54f9acf1b92e26d6e7ed82a3c3.png)

# 14. CSS gap Property

**Example**

-   Set the gap between rows *and* columns to 50px:

.grid-container {  
gap: 50px;  
}

**Output**

![](media/adf637de0f0165275e49371aea59197d.png)

# 15. CSS margin Property

**Example**

-   Set the margin for all four sides of a \<p\> element to 35 pixels:

p {  
margin: 35px;  
}

**Output**

![](media/fbfafb1e5dcdb218444189183922d020.png)

# 16. CSS padding Property

**Example**

-   Set the padding for all four sides of a \<p\> element to 35 pixels:

p {  
padding: 35px;  
}

**Output**

![](media/cb5cfbf1aad2ab6a78ab4f3eeb4957ab.png)

# 17. CSS scroll-behavior Property

**Example**

-   Add a smooth scrolling effect to the document:

html {  
scroll-behavior: smooth;  
}

**Output**

**![](media/1abdf5e69160c0def898aa922cb94687.png)**

# 18. CSS table-layout Property

**Example**

-   Set different table layout algorithms:

table.a {  
table-layout: auto;  
width: 180px;  
}

table.b {  
table-layout: fixed;  
width: 180px;  
}

**Output**

![](media/ecc683fc3cb44744cd5519f96f11a011.png)

# 19. CSS text-align Property

**Example**

-   Set the text alignment for different \<div\> elements:

div.a {  
text-align: center;  
}

div.b {  
text-align: left;  
}

div.c {  
text-align: right;  
}

div.c {  
text-align: justify;  
}

**Output**

![](media/bbe52e69c7b2bdd7646db5b89f9c0135.png)

# 20. CSS text-decoration-color Property

**Example**

-   Set the color of the text-decoration to red:

p {  
text-decoration: underline;  
text-decoration-color: red;  
}

**Output**

![](media/056bbfc34fd2d4c3bd784888ae47f06e.png)

# 21. CSS text-decoration-style Property

**Example**

-   Set different types of text-decoration styles:

div.a {  
text-decoration-line: underline;  
text-decoration-style: solid;  
}

div.b {  
text-decoration-line: underline;  
text-decoration-style: wavy;  
}

div.c {  
text-decoration-line: underline;  
text-decoration-style: double;  
}

div.d {  
text-decoration-line: overline underline;  
text-decoration-style: wavy;  
}

**Output**

![](media/68f6c95327b40966643dcac7ac1f4409.png)

# 22. CSS white-space Property

**Example**

-   Demonstrate different values of the white-space property:

p.a { white-space: nowrap; }

p.b { white-space: normal; }

p.c { white-space: pre; }

**Output**

![](media/38ff0a5d5213ef2fa3900c473c2b9862.png)

# 23. CSS word-spacing Property

**Example**

-   Specify that the space between words in \<p\> elements should be 30 pixels:

p {  
word-spacing: 30px;  
}

**Output**

![](media/e972d2b39d91554e88cd9a2cc0bf4695.png)

# 24. CSS word-wrap Property

**Example**

-   Allow long words to be able to break and wrap onto the next line:

div {  
word-wrap: break-word;  
}

**Output**

![](media/724eb0d875f3ec8945e0e4e05b8ca327.png)

# 25. CSS writing-mode Property

**Example**

-   Specify whether lines of text are laid out horizontally or vertically:

p.test1 {  
writing-mode: horizontal-tb;  
}

p.test2 {  
writing-mode: vertical-rl;  
}

span.test2 {  
writing-mode: vertical-rl;  
}

**Output**

**![](media/82035a6ad39255b2a237b7609843171d.png)**

# 26. References

1.  https://www.w3schools.com/cssref/css3_pr_animation.asp
2.  https://www.w3schools.com/cssref/pr_background-color.asp
3.  https://www.w3schools.com/cssref/pr_background-attachment.asp
4.  https://www.w3schools.com/cssref/pr_border.asp
5.  https://www.w3schools.com/cssref/pr_border-width.asp
6.  https://www.w3schools.com/cssref/pr_text_color.asp
7.  https://www.w3schools.com/cssref/css3_pr_column-count.asp
8.  https://www.w3schools.com/cssref/css3_pr_column-gap.asp
9.  https://www.w3schools.com/cssref/pr_text_direction.asp
10. https://www.w3schools.com/cssref/css3_pr_filter.asp
11. https://www.w3schools.com/cssref/pr_font_font-size.asp
12. https://www.w3schools.com/cssref/pr_font_font-style.asp
13. https://www.w3schools.com/cssref/pr_font_font-variant.asp
14. https://www.w3schools.com/cssref/pr_margin.asp
15. https://www.w3schools.com/cssref/css3_pr_gap.asp
16. https://www.w3schools.com/cssref/pr_padding.asp
17. https://www.w3schools.com/cssref/pr_scroll-behavior.asp
18. https://www.w3schools.com/cssref/pr_tab_table-layout.asp
19. https://www.w3schools.com/cssref/pr_text_text-align.asp
20. https://www.w3schools.com/cssref/css3_pr_text-decoration-color.asp
21. https://www.w3schools.com/cssref/css3_pr_text-decoration-style.asp
22. https://www.w3schools.com/cssref/pr_text_white-space.asp
23. https://www.w3schools.com/cssref/pr_text_word-spacing.asp
24. https://www.w3schools.com/cssref/css3_pr_word-wrap.asp
25. https://www.w3schools.com/cssref/css3_pr_writing-mode.asp

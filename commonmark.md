---
marp: true
 
theme: default
paginate: true
author: "Manan Sharma"
transition: fade
backgroundImage: url('https://marp.app/assets/hero-background.svg')
title: Introducton to markdown
header: '**Modular** Equipment Private Limited'
footer: Manan **Sharma**

---
<!---
_header: ''
_footer: ''
_paginate: false

![bg right contain](https://i.imgur.com/2cRvXIH.jpeg)
-->

<Style scoped>
  h1
  {
    font-size: 56px
  }
</Style>

![bg right contain opacity:.25](https://i.imgur.com/sBC8NJd.jpeg)

# Introduction to Markdown

## Manan Sharma

### **Modular** Equipment Private Limited

---

# Markdown

**Markdown** is a simple way to format text that looks great on any device. It doesn’t do anything fancy like change the font size, color, or type — just the essentials, using keyboard symbols you already know.

---

## Introduction

Each lesson introduces a single Markdown concept with an example. When you see a red pulsing circle in the example, select to examine it for details.

After studying the example, try a few practice exercises with your new knowledge. Skip to any lesson at any time via the navigation controls. Experiment and have fun!

---

## Emphasis

### Bold and Italics

- To create bold or italic, wrap with asterisks * or underscores _.
- To avoid creating bold or italic, place a backslash in front \* or \_.
- Two ** or __ will make the enclosed text bold.
  - Like &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \*\*text\*\*
  - Or &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \_\_text\_\_
- One * or _ will make the enclosed text italic.
- The same character must be used to open and close emphasis.
- There must be no space between the * or _.

---

### Example - Bold

Making the words “American" bold:

The music video for Rihanna’s song \*\*American\*\* Oxygen depicts various moments from \_\_American\_\_ history, including the inauguration of Barack Obama.

#### Results in **Bold**

The music video for Rihanna’s song **American** Oxygen depicts various moments from **American** history, including the inauguration of Barack Obama.

---

### Example - Italics

Making the word “six” italic.

Why, sometimes I’ve believed as many as \_six\_ impossible things before breakfast.

#### Results in ***Italics***

Why, sometimes I’ve believed as many as *six* impossible things before breakfast.

---

### Style should be consistent

The configured strong style can be a specific symbol to use ("asterisk", "underscore"), or can require that usage be consistent within the document.

#### Rationale: **Consistent formatting** makes it easier to understand a document

---

### Example - Bold & Italics

Makeing the whole sentence bold, and italicize the word “must”.

\*\*Everyone \*must\* attend the meeting at 5 o’clock today.\*\*

#### Results in - **Bold** & ***Italics***

**Everyone *must* attend the meeting at 5 o’clock today.**

---

### Example - Disabling the formatting

#### Consider

I am totally awesome. *
\* for certain very small values of awesome.

#### Without escape character "\". It results in

I am totally awesome. *

- for certain very small values of awesome.

---

### Example - Disabling the formatting (contd.)

Lets change the last line so the * is visible:

I am totally awesome. *
\\* for certain very small values of awesome.

#### Resulting in

I am totally awesome. *
\* for certain very small values of awesome.

---

## Paragraphs

A paragraph is consecutive lines of text with one or more blank lines between them.

For a line break, add either a backslash \ or two blank spaces at the end of the line. That is, use either two spaces or a backslash \ at the end of a line to create a line break.

A blank line is any line without text or a line that contains nothing but spaces or tabs.

---

### Example - Paragraphs

#### Organize the following two sentences into two paragraphs

The sky above the port was the colour of television, tuned to a dead channel. It was a bright cold day in April, and the clocks were striking thirteen.

#### To do this, we will add backspace \

The sky above the port was the color of television, tuned to a dead channel.\
It was a bright cold day in April, and the clocks were striking thirteen.

---

### Example - Poem

#### Format this poem so the lines end exactly as shown

Only my heart knows the pleasures of this love,
Only my heart knows the sorrows it has brought.
Only my heart knows the oppressions of time,
Only my heart knows the times it was pestered.

#### As without any formatting, It ends up like

Only my heart knows the pleasures of this love, Only my heart knows the sorrows it has brought. Only my heart knows the oppressions of time, Only my heart knows the times it was pestered.

---

### Example - Poem (contd.)

#### So we add \ after each line

Only my heart knows the pleasures of this love,\\
Only my heart knows the sorrows it has brought.\\
Only my heart knows the oppressions of time,\\
Only my heart knows the times it was pestered.

#### Hence, it results in new lines

Only my heart knows the pleasures of this love,
Only my heart knows the sorrows it has brought.
Only my heart knows the oppressions of time,
Only my heart knows the times it was pestered.

---

## Headings

Starting a line with a hash # and a space makes a header.

The more #, the smaller the header.

This is same as having <**H** *n*> tag in HTML.
THat is **<H1> <H2> <H3>** and so on.

---

## Headings (contd.)

For heading level one, there is an alternate “underline” style using =
\
\
&nbsp;Heading 1  
\=======

### Results in forming a level 1 heading

# Heading  1

---

## Headings (contd..2)

Similar to Heading 1
For heading level two, there is an alternate “underline” style using -

&nbsp;Heading 2
&nbsp;\------------

### Results in forming a level 2 heading

## Heading  2

---

## Headings (contd..3)

You can optionally add more # at the end to close the header. You don’t need to match the number of # used at the beginning.

There must be a space between the # and the heading title.

The title can also contain formatting like bold and italic.

---

# Heading 1

## Heading 2

### Heading 3

---

# Title

## Heading

### Sub Heading

## Another heading

---

### Example - Headings

Chapter 1
Something about the room made him uneasy.
Chapter 2
It's behind you! Hurry before it

#### Adding \# will result in

## Chapter 1

Something about the room made him uneasy.

## Chapter 2

It's behind you! Hurry before it catches you.

---

### Example 2 - Headings

#### Consider the following

After the Big Bang
A brief summary of time
Life on earth
10 billion years
You reading this
13.7 billion years

---

### Example 2 - Headings (contd.)

#### Making the first line a level 1 header, and the lines beginning with “Life” and “You” level 2 headers

\# After the Big Bang
A brief summary of time
\## Life on earth
10 billion years
\## You reading this
13.7 billion years

---

### Example 2 - Headings (contd..2)

#### Will result in

# After the Big Bang

A brief summary of time

## Life on earth

10 billion years

## You reading this

13.7 billion years

---

## Blockquotes

To create a blockquote, start a line with greater than > followed by an optional space.
Blockquotes can be nested, and can also contain other formatting.

To keep the quote together, blank lines inside the quote must contain the > character.
The space between the > and the quoted text is optional.

---

### Example - Blockquotes

#### Consider this statement

The quote “Somewhere, something incredible is waiting to be known” has been ascribed to Carl Sagan.

#### Making this quote a proper blockquote & removing the “” characters, too

The quote

> Somewhere, something incredible is waiting to be known

has been ascribed to Carl Sagan.

---

### Example 2 - Blockquotes

My favourite Miss Manners quotes:
Allowing an unimportant mistake to pass without comment is a wonderful social grace.
Ideological differences are no excuse for rudeness.

#### Adding blockquote \> results in

My favourite Miss Manners quotes:

> Allowing an unimportant mistake to pass without comment is a wonderful social grace.
> Ideological differences are no excuse for rudeness.

---

## Lists

Unordered lists can use either asterisks *, plus +, or hyphens - as list markers.

Ordered lists use numbers followed by period . or right parenthesis ).

A space is required after each list character.

---

## Lists (contd.)

Use any of *, + or - to make a list. Each list must consistently use the same character.

Ordered lists start with a number followed by a . or ) and a space.

If you don’t want a list? Use backslash to escape:

```Markdown
12\. An even number.
```

---

## Lists (contd..2)

### You don't have to use ordered numbers

```Markdown
1. One
1. Two

and

5. Five
7. Six
```

---

#### Both render an ordered list, the latter will start at 5

1. One
2. Two

and

5. Five
7. Six

---

### Example - Unordered Lists

Writing items in new like like this:

```Markdown
Flour
Cheese
Tomatoes
```

Renders as

Flour Cheese Tomatoes

---

#### Making this into an unordered list by adding a dash - and a space

```Markdown
- Flour
- Cheese
- Tomatoes
```

Will render as

- Flour
- Cheese
- Tomatoes

---

### Example - Ordered Lists

Similarly, consider

```Markdown
Four steps to better sleep:
Stick to a sleep schedule
Create a bedtime ritual
Get comfortable
Manage stress
```

Can be made into an ordered list like this

```Markdown
Method 1:
1. Four steps to better sleep:
1. Stick to a sleep schedule
1. Create a bedtime ritual
1. Get comfortable
1. Manage stress

```

---

#### Another way is

```Markdown
Method 2:
1) Four steps to better sleep:
2) Stick to a sleep schedule
3) Create a bedtime ritual
4) Get comfortable
5) Manage stress

```

#### Both will render as

1) Four steps to better sleep:
2) Stick to a sleep schedule
3) Create a bedtime ritual
4) Get comfortable
5) Manage stress

---

### Example - Numbers not Lists

Observe this

```Markdown
1986. What a great season. Arguably the finest season in the history of the franchise.
```

Renders as

1986. What a great season. Arguably the finest season in the history of the franchise.

Here 1986 is rendered as a numbered bullet point, as a list item. We don’t want a list here. To avoid this, we have to use a \, the escape character to render as a number rather than a list.

```Markdown
1986\. What a great season. Arguably the finest season in the history of the franchise.
```

---

## Links

Links can be either inline with the text, or placed at the bottom of the text as references.

Link text is enclosed by square brackets [], and for inline links, the link URL is enclosed by parens ().

Don’t put a space between any of the brackets.

---

We can also use relative URLs such as /example.html

```Markdown
[text](http://a.com)

[text][id]
⋮
[id]: http://b.org/ "title"
```

The link definition can be placed anywhere after a blank line, but is generally near the bottom.

Definition identifiers may consist of letters, numbers, spaces, and punctuation. They are not case sensitive. The title of the link is optional.

---

URLs may not become links in Markdown until enclosed in < and >. Turn this URL into a link:

```Markdown
You can do anything at https://html5zombo.com
You can do anything at <https://html5zombo.com>
```

Will render as
You can do anything at https\://html5zombo.com
You can do anything at <https://html5zombo.com>

Observe that only the latter link is clickable.

---

### Example - Links: Inline style

Lets try to link “University of Rwanda” to <http://www.ur.ac.rw> with an inline link in the following text.

The University of Rwanda was formed in 2013 through the merger of Rwanda’s seven public institutions of higher education.

To do so, we have to do something like this:

```Markdown
The [University of Rwanda](http://www.ur.ac.rw) was 
formed in 2013 through the merger of Rwanda’s seven 
public institutions of higher education.
```

Resulting in
The [University of Rwanda](http://www.ur.ac.rw) was formed in 2013 through the merger of Rwanda’s seven public institutions of higher education.

---

### Example - Links: Reference style

Lets link both of the words “hurricane” to the Wikipedia entry at <https://w.wiki/qYn> with a reference style link:

```Markdown
[Hurricane][1] Erika was the strongest and longest-lasting 
tropical cyclone in the 1997 Atlantic [hurricane][1] season.

[1]:https://w.wiki/qYn
```

Resulting in

[Hurricane][1] Erika was the strongest and longest-lasting tropical cyclone in the 1997 Atlantic [hurricane][1] season.

[1]:https://w.wiki/qYn

---

## images

Images are almost identical to links, but an image starts with an exclamation point !.

```Markdown
![alt](cat.png)

![alt][id]

[id]: dog.jpg "title"
```

Alternate (alt) text is displayed when the image can't be shown, or for the visually impaired.
It's fine to leave this blank but the [] is required.

---

You can also use complete URLs, such as <http://a.com/dog.jpg>

Make sure there are no spaces between the brackets.

Definition identifiers may consist of letters, numbers, spaces, and punctuation. They are not case sensitive.

The link definition can be placed anywhere after a blank line, but is generally near the bottom.

The title of the image is optional.

A title provides more textual detail about what the image shows or contains.

---

### Example - Images

```Markdown
https://commonmark.org/help/images/favicon.png
```

Makeing this image appear – no need for alt text or title, leave those blank, by changing it to the following

```Markdown
![](https://commonmark.org/help/images/favicon.png)
```

![Markdown](https://commonmark.org/help/images/favicon.png)

---

### Example - Images, referenced and alternate text

Adding alt text of Logo and title of Creative Commons licensed to this image

```Markdown
![][1]

[1]: https://commonmark.org/help/images/favicon.png
```

By changing this to

```Markdown
![Logo][1]

[1]: https://commonmark.org/help/images/favicon.png "Creative Commons licensed"
```

![Logo][2]

[2]: https://commonmark.org/help/images/favicon.png "Creative Commons licensed"

---

## CODE

To create inline code, wrap with backticks `.

To create a code block, either indent each line by 4 spaces, or place 3 backticks ``` on a line above and below the code block.

```Markdown
Inline `code` 
```

```Markdown
    Or indent 4 spaces for the whole line.
```

&#96;&#96;&#96;
Or use 3 backticks to create multi line code block.
&#96;&#96;&#96;

---

- A code block or span displays every character inside exactly as it was typed.
- Remember, one level of indentation in a code block equals 4 spaces or one tab.
- An indented code block continues until it reaches a line that is not indented.
3 backticks on a single line ``` marks the beginning and end of a code block.
- This is sometimes called a “code fence” or 'code block'.

---

### Example - Inline Code

Lets try to format only the math in this sentence as inline code in the following statement.

When x = 3, that means x + 2 = 5.

To do so we do something like this:

```text
When 'x = 3', that means 'x + 2 = 5'
```

Resulting in somethinflike this:

When 'x = 3', that means 'x + 2 = 5'

---

### Example - Indented Code Block

```Markdown
Jeff  15
Sam   11
Robin  6
```

Renders in a single line. Lets format the score table as an indented code block.

    Jeff  15
    Sam   11
    Robin  6

---

### Example - Code Block

A loop in JavaScript:

```Javascript
var i;
for (i=0; i<5; i++) {
  console.log(i); // You always console JS devs
}
```

What numbers will this print?

```bash
0
1
2
3
4
```

---

We can add an optional language identifier to enable syntax highlighting in your fenced code block. To do so, we can add the identifier tailing the opening ```. Like

\```Java
\```Javascript
\```Ruby
\```bash
And many more.

The code on the previous slide was done in the same manner.

---

## Nested Lists

To nest one list within another, indent each item in the sublist by four spaces. You can also nest other elements like paragraphs, blockquotes or code blocks.

- Item
    1. First Subitem
    2. Second Subitem
- Item
  - Subitem
  - Subitem
- Item

---

The list on the previous slide was obtained by doing the formatting like the following:

```Markdown
* Item
    1. First Subitem
    2. Second Subitem
* Item
    - Subitem
    - Subitem
* Item
```

- You can mix ordered and unordered lists.
- To nest a paragraph or blockquote, indent by either 4 spaces or one tab.
- To nest a code block, indent by either 8 spaces or two tabs, or use a ``` code block.

---

### Example - Unordered Nested List

Lets convert the items under "Fruit" and "Dairy" into a sublist.

Fruit
Apple
Orange
Banana
Dairy
Milk
Cheese
Curd

---

#### Lets do something like this

```Markdown
* Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese
  * Curd
```

---

Which will result in such format

- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese
  - Curd


---

### Example - Ordered Nested List

Here are the winners of the given tournaments. Lets do an ordered list on the bases of rankings.

```Markdown
+ World Cup 2014
Germany
Argentina
Netherlands
+ Rugby World Cup 2015
New Zealand
Australia
South Africa
```

---

To do so, lets addeight spaces and numbering

```Markdown
+ World Cup 2014
  1. Germany
  2. Argentina
  3. Netherlands
+ Rugby World Cup 2015
  1. New Zealand
  2. Australia
  3. South Africa
```

---

### The final result is something like this

+ World Cup 2014
  1. Germany
  2. Argentina
  3. Netherlands
+ Rugby World Cup 2015
  1. New Zealand
  2. Australia
  3. South Africa

---

Observe the given recepie. The content under each numbered item isn’t nested properly, lets try to fix it

```Markdown
1. Ingredients

- spaghetti
- marinara sauce
- salt

2. Cooking

Bring water to boil, add a pinch of salt and spaghetti. Cook until pasta is **tender**.

3. Serve

Drain the pasta on a plate. Add heated sauce. 
> No man is lonely eating spaghetti; it requires so much attention.

Bon appetit!
```

---

To do so, the following  edits may do a good job.

```Markdown
1. Ingredients
    - spaghetti
    - marinara sauce
    - salt

2. Cooking
   Bring water to boil, add a pinch of salt and spaghetti. Cook until pasta is **tender**.

3. Serve
   Drain the pasta on a plate. Add heated sauce. 
   > No man is lonely eating spaghetti; it requires so much attention.

   Bon appetit!
```

---

<!-- _header: "" -->

And the final result:

1. Ingredients

    - spaghetti
    - marinara sauce
    - salt

2. Cooking

   Bring water to boil, add a pinch of salt and spaghetti. Cook until pasta is **tender**.

3. Serve

   Drain the pasta on a plate. Add heated sauce. 

   > No man is lonely eating spaghetti; it requires so much attention.

   Bon appetit!

---
<!--
https://wallpaper-mania.com/wp-content/uploads/2018/09/High_resolution_wallpaper_background_ID_77700405825.jpg
-->

<style scoped>
  h2
  {
    color: white
  }

  p
  {
    color: white
  }
</style>

![bg](https://www.freeppt7.com/uploads/191106/1-191106101U2C4.jpg)

## Tables

A table is an arrangement of data in rows and columns. To add a table in Markdown, use the vertical line | to separate each column, and use three or more dahses --- to create each column's header. A vertical line should also be added at either end of the row. The output will look exactly the same.

```Markdown
|   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
```

Results in

|  |  |  |  |  |  |  |
|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |

Which is an empty table. It wraps around the content inside.

---

<style scoped>
  h3
  {
    color: white
  }
</style>

![bg](https://www.freeppt7.com/uploads/191106/1-191106101U2C4.jpg)

```Markdown
|S.No.|A|B|C|D|E|
|--|--|--|--|--|--|
|1|A1|B1|C1|D1|E1|
|2|A2|B2|C2|D2|E2|
|3|A3|B3|C3|D3|E3|
```

### Results in a table like this

|S.No.|A|B|C|D|E|
|--|--|--|--|--|--|
|1|A1|B1|C1|D1|E1|
|2|A2|B2|C2|D2|E2|
|3|A3|B3|C3|D3|E3|

---

### Alignment

You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.

```Markdown
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: | <-- Here
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

You can’t use headings, blockquotes, lists, horizontal rules, images, or most HTML tags.

---

<style scoped>
  h3
  {
    color: white
  }
</style>

### Example - Tables

![bg](https://www.freeppt7.com/uploads/191106/1-191106101U2C4.jpg)

| DIVISION | DT Code | Functional ID | DT location | KVA    Rating |
|---|---|---|---|---|
| CHANDNI   CHOWK | DL-1LDTRKT99009297 | 1S-DL-YP-CTC-DCCK-0104-LHR037 | CHURCH MISSION ROAD | 990 |
| CHANDNI   CHOWK | DL-1LDTRNF99006236 | 1S-DL-YP-CTC-DCCK-0104-LHR033 | KATRA BARYAN:ID | 990 |
| CHANDNI   CHOWK | DL-1LDTRKT99055443 | 1S-DL-YP-CTC-DCCK-0103-THL014 | KUMAR CINEMA:PKG | 990 |
| CHANDNI   CHOWK | DL-1LDTRVJ63011250 | 1S-DL-YP-CTC-DCCK-0104-LHR028 | KATRA NEEL:PM | 630 |
| CHANDNI   CHOWK | DL-1LDTRNF63013037 | 1S-DL-YP-CTC-DCCK-0105-HAM015 | DELHI POLYTECHNIC:ID | 630 |
| CHANDNI   CHOWK | DL-1LDTRAT63010650 | 1S-DL-YP-CTC-DCCK-0105-HAM034 | YAMUNA BAZAR | 630 |
990 |
| CHANDNI   CHOWK | DL-1LDTRNF99054838 | 1S-DL-YP-CTC-DCTE-GCT1-CTC058 | TOWN HALL SUBSTATION | 990 |
| CHANDNI   CHOWK | DL-1LDTREC9901415 | 1S-DL-YP-CTC-DCCK-0104-LHR051 | NEW HAUZ QUAZI(COMPLAIN CENTRE):ID | 990 |

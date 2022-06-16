# Markdown

[Markdown language](#langmarkdown)
- [1. Phrase Emphasis](#phrase)
- [2. Links/Images](#linkandimage)
- [3. Headers](#header)
- [4. Lists](#list)
- [5. Blockquotes](#blockquotes)
- [6. Code Spans](#codespans)
- [7. Code Blocks](#codeblocks)
- [8. Horizontal Rules](#horirule)
- [9. Manual Line Breaks](#manuline)
- [10. Table](#table)
- [Tip](#tip)


<a name="langmarkdown"></a>
## Markdown language

Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML). (Markdown files have the extension .md)

This language is quite simple, you can read [here](http://daringfireball.net/projects/markdown/syntax) to know how to use it.

# Syntax Cheatsheet:
<a name="phrase"></a>
## Phrase Emphasis
```
*italic*   **bold**
_italic_   __bold__
```
<a name="linkandimage"></a>
## Links
#### Inline:
`An [example](http://url.com/ "Title")`

#### Reference-style labels (titles are optional):
```
An [example][id]. Then, anywhere
else in the doc, define the link:

   [id]: http://example.com/  "Title"
```
## Images
#### Inline(titles are optional):
`![alt text](/path/img.jpg "Title")`

#### Reference-style:
```
![alt text][id]

[id]: /url/to/img.jpg "Title"
```
<a name="header"></a>
## Headers

#### Setext-style:
```
Header 1
========

Header 2
--------
```
#### atx-style (closing #'s are optional):
```
# Header 1 #
## Header 2 ##
###### Header 6
```
<a name="list"></a>
## Lists

#### Ordered, without paragraphs:

```
1.  Foo
2.  Bar
```

#### Unordered, with paragraphs:

```
*   A list item.

    With multiple paragraphs.

*   Bar
```
#### You can nest them:
```
*   Abacus
    * answer
*   Bubbles
    1.  bunk
    2.  bupkis 
        * BELITTLER
    3. burper
*   Cunning
```
<a name="blockquotes"></a>
## Blockquotes
```
> Email-style angle brackets
> are used for blockquotes.

> > And, they can be nested.

> #### Headers in blockquotes
> 
> * You can quote a list.
> * Etc.
```
<a name="codespans"></a>
## Code Spans
```
`<code>` spans are delimited
by backticks.

You can include literal backticks
like `` `this` ``.
```
<a name="codeblocks"></a>
## Preformatted Code Blocks
Indent every line of a code block by at least 4 spaces or 1 tab.

This is a normal paragraph.
```
    This is a preformatted
    code block.
```
<a name="horirule"></a>
## Horizontal Rules
Three or more dashes or asterisks:
```
---

* * *

- - - - 
```
<a name="manuline"></a>
## Manual Line Breaks
End a line with two or more spaces:
```
Roses are red,   
Violets are blue.
```

## Table

```
| Row \Column | Column 1 | Column 2 | Column 3 |
|-------|-------|-------|-------|
| Row 1 | 1 x 1 | 1 x 2 | 1 x 3 |
| Row 2 | 2 x 1 | 2 x 2 | 2 x 3 | 
| Row 3 | 3 x 1 | 3 x 2 | 3 x 3 | 
```

## Tip
Use the page http://markdownlivepreview.com/ paste in the markdown you write and preview to edit accordingly.




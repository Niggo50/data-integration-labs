# Table of Contents
- [Text](#Text)
- [Lists](#Lists)
- [Links and images](#Links-and-images)
- [Code](#Code)
- [Quotes](#Quotes)
- [Tables](#Tables)
- [Layout](#Layout)
- [GitHub extras](#GitHub-extras)

# Text
- [Headings](#Headings)
- [Paragraphs and line breaks](#Paragraphs-and-line-breaks)
- [Italic, bold and both](#Italic-bold-and-both)
- [Strikethrough](#Strikethrough)
- [Inline code](#Inline-code)
- [Escaping a character such as `*`](#Escaping-a-character-such-as-)

## Headings
Adding # to the front of a text will turn it into a heading. The more # there are in front of the text the smaller the text will be.   
Example:
```
# Heading
## Heading
### Heading
#### Heading
##### Heading
###### Heading
####### Heading
```
# Heading
## Heading
### Heading
#### Heading
##### Heading
###### Heading
####### Heading

## Paragraphs and line breaks
To create paragraphs leave a line blank. To beginn a new line add two or more whitespaces at the end of the line.  
Example:
```
Hi i want to start a new line.  
Hello

Hello
```
Hi i want to start a new line.  
Hello

Hello

## Italic, bold and both
To change the text to italic or bold add * at both ends of the text.  
Use one * at each end for italic, two for bold and three for both.  
Example:
```
I like *italic*  
I like **bold**
I Like ***italic and bold***
```
I like *italic*  
I like **bold**  
I Like ***italic and bold***

## Strikethrough
Add ~~ at each end of the text to create strikethrough text.  
Example
```
~This is right~
```
~This is right~

## Inline code
To use inline code add ` at the start and at the end of your code.  
Example
```
To print something in python use the `print()` function.
```
To print something in python use the `print()` function.

## Escaping a character such as `*`
If you want to use characters such as `*` or `#` without accidentally changing your text use a `\` infront of the character.  
Example: 
```
\* Hello \*
```
\* Hello \*

# Lists
- [Unordered, ordered and nested lists](#unordered-ordered-and-nested-lists)
- [Task lists](#Task-lists)

## Unordered, ordered and nested lists
To create an unordered list add `-` infront of your listed texts.  
To create an ordered list add numbers infront of your listed texts.  
To nest two lists with each other indent the texts in the sublist by two whitespaces.  
Example:
```
- first
- second
- third

1. first
2. second
3. third

- first
  - second
  - third
```
- first
- second
- third

1. first
2. second
3. third

- first
  - second
  - third

## Task lists
To create task lists use `- [ ]` for non-complete tasks and `- [x]` for completed tasks.  
Example:
```
- [ ] Bananas
- [x] Milk
```
- [ ] Bananas
- [x] Milk

# Links and images
- [Inline and reference-style links](#inline-and-reference-style-links)
- [A relative link to another file in your repository](#a-relative-link-to-another-file-in-your-repository)
- [A link to a section](#a-link-to-a-section)
- [An image with alt text](#An-image-with-alt-text)

## Inline and reference-style links
To add a reference-link to a text put the text into `[]` and add a number afterwards in `[]`. Put the same number after the text in `[]:` and the reference-link afterwards in `<>`.   
You can also add the reference-link after the text in `()`.
Example:
```
I use [Google](https://www.google.com)

I use [Google][1].

[1]: https://www.google.com
```
I use [Google](https://www.google.com).

I use [Google][1].

[1]: https://www.google.com

## A relative link to another file in your repository
To refer to a file in your repository put the directory of the file in the reference `()`.
```
Check out my [README](../../README.md)
```
Check out my [README](../../README.md)

## A link to a section
To create a link to a section put the section-heading in the reference `()` with the `#`.  
Example:
```
Reference to [A link to a section](#A-link-to-a-section).
```
Reference to [A link to a section](#A-link-to-a-section).

## An image with alt text
To add an image with al text add an `!` befor the alt text in `[]` followed by the reference in `()`. You can add a title after the reference in `"` if you want. If you want to refer a link to the image encase everything in `[]` and add the link afterwards `()`.
Example:
```
[![Flicker](./flicker.jpg "Northern flicker, male")](https://en.wikipedia.org/wiki/Northern_flicker#/media/File:Northern_yellow-shafted_flicker_male_(33737)_(cropped).jpg)
```
[![Flicker](./flicker.jpg "Northern flicker, male")](https://en.wikipedia.org/wiki/Northern_flicker#/media/File:Northern_yellow-shafted_flicker_male_(33737)_(cropped).jpg)

# Code
## Fenced code blocks with syntax highlighting for Python, Bash and JSON
To add a code block put ``` in the lines before and after the code block.  
Example:
````
```
your function
```
````
```
your function
```

# Quotes
- [Blockquotes, nested and with formatting](#Blockquotes-nested-and-with-formatting)
- [Alerts, like the boxes in this lab](#alerts-like-the-boxes-in-this-lab)

## Blockquotes, nested and with formatting
To put a quote into a block add a `>` at the start of the quote.  
Example:
```
>This is my quote.  
>It is more than one line long.
```

>This is my quote.  
>It is more than one line long.

## Alerts, like the boxes in this lab
To add an alert box you have to put the heading of the alert in `[!NOTE]` at the line in front of the alert. The alert also has to have `>` at the start of each line.  
Other alerts are `[!TIP]`, `[!WARNING]`, `[!CAUTION]` and `[!IMPORTANT]`
Example:
```
>[!NOTE]
>This is a useful note.

>[!TIP]
>This is a useful tip.

>[!WARNING]
>This is a useful warning

>[!CAUTION]
>You should be cautious of this.

>[!IMPORTANT]
>This is important

```
>[!NOTE]
>This is a useful note.

>[!TIP]
>This is a useful tip.

>[!WARNING]
>This is a useful warning

>[!CAUTION]
>You should be cautious of this.

>[!IMPORTANT]
>This is important

# Tables
To create a table use `|` to separate columns and `---` to separate rows.  
Example:
```
|Month|Days|
|-----|----|
|January|31|
|February|28\|29|
|March|31|
```
|Month|Days|
|-----|----|
|January|31|
|February|28\|29|
|March|31|

# Layout
- [Horizontal rules](#Horizontal-rules)
- [Collapsed sections, like the hints in this lab](#Collapsed-sections-like-the-hints-in-this-lab)
- [Comments that do not render](#Comments-that-do-not-render)

## Horizontal rules
To create horizontal rules put `***`, `---` or `___` i a line.  
Example:
```
---
___
***
```
---
___
***

## Collapsed sections, like the hints in this lab
To create collapsed sections put `<details>` at the strat and `</details>` end of the section in a seperate line.  
Put `<summary>` at the second line followed by the teaser-text for the section and `</summary>` at the end.   
Example:

```
<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section.

You can add an image or a code block, too.
</details>

```
<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section.

You can add an image or a code block, too.
</details>

## Comments that do not render
To create comments in your markdown text that do not render put the text into `[]` followed by `: #`.  
Example:
```
Here's a paragraph that will be visible.

[This is a comment that will be hidden.]: # 

And here's another paragraph that's visible.
```
Here's a paragraph that will be visible.  

[This is a comment that will be hidden.]: # 

And here's another paragraph that's visible.

# GitHub extras
- [Foornotes](#footnotes)
- [Emoji shortcodes](#emoji-shortcodes)

## Footnotes
To create footnotes put the footnote identfier into `[^]` and add the footnote later using the identifier followed by the text.  
Example:
```
This is a footnote. [^1]
[^1]: Hello
```
This is a footnote. [^1]
[^1]: Hello

## Emoji shortcodes
To insert emojis use the shortcodes in [this](https://gist.github.com/rxaviers/7360908) list.

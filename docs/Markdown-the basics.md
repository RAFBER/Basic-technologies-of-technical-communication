---
layout: default
title: Markdown
nav_order: 2
---

# Markdown-the basics
{: .no_toc}

![Markdown logo](/assets/images/Markdown_logo.jpg)

## Table of contents
{: .no_toc}

1. TOC
{:toc}


# 1. Introduction
## What is Markdown?  
Markdown is a simple text format. This is the so-called “quick documentation” standard in IT branch and related fields. It is mainly used to generate HTML files. With Markdown is possible to create the web pages without any additional tools. 

## Advantages
* Very simple format, readable also without processing
* Documentation can be expanded to any size also by attach another files
* Easily manage large numbers of documents and reuse
* Free tools to write in Markdown with preview
* Other input and output formats can be generated because Markdown is a simple text file that does not impose anything
* The contents can be downloaded and modified in any way
* Appearance separated from the content by preview window

## Disadvantages
* Markdown is a simple to simple things but more difficult to more complicated (e.g. tables, formulas)
* Markdown is a text format – during the transfer between different tools/technologies needs to be aware of the line break and character encoding

# 2. Functionality

## 2.1. Main function of the text format 

### 2.1.1 Tittle

<!-- Example for title -->
    Title
    =====

**Note:** The "Tittle" should be one in current document otherwise the document structure will be wrong. 

### 2.1.2 Paragraph

<!--Example of paragraph of text-->
    This is a paragraph of text.

    This is another paragraph of text.

    This is a line.  
    This is another line.  
    This is not a new line.  

<!--Example of another paragraph of text-->
    Paragraph of text that spans over he line. See how this displays when I write and write and write. What happens when I press enter? Nothing!  
    If I want a new line, I put two spaces and them Enter. This is still the same paragraph.

### 2.1.3 Bold, Italic, Quote

<!--Example for bold text-->
* See how to insert **bold** text!  
*     See how to insert **bold** text!

<!--Example for Italic-->
* And that's *How italic is defined*.

* Example for Quote
* A wise man once said:
  >Don't listen to me!  
  >Why would you?

  And he was right.


## 2.2 Creating a document structure 

### 2.2.1 Headers

<!--Example for Headers-->
    # Header of chapter 1
    This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.
    # Header of chapter 2
    This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.

    ## Chapter 2.1
    Chapter text.
    ## Chapter 2.2
    More chapter text.

    Or (second option)

    # 1. Header of chapters
    This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.
    # 2. Header of chapter
    This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.This is a paragraph of text.
    ## 2.1 Chapter
    Chapter text.
    ## 2.2 Chapter
    More chapter text.
    ### 2.2.1 Chapter
    More chapter text.- [Sample document](#sample-document)

### 2.2.2 Table of contents

To create the *Table of contents* proceed as follows:  
* Click the mouse cursor in the proper place of the document where you would like to implement the *Table of contents*
* Use the keyboard shortcut Ctrl+Shift+P
* Enter the "create" in command field and choose the option: *Markdown All in One: Create Table of Contents*  
  **Note:** The Markdown All in One extension must be previously installed. 

   ![Table of contents](/assets/images/ToC_1.jpg)

For the extension installation procedure please refer to the document *Visual Studio Code - useful options*  
[Visual Studio Code – useful options](Visual_Studio_Code–useful_options.md)

<!--Example for Bullet list-->
### 2.2.3 Bullet list
* bullet
* another bullet
* more bullets
<!--Example for Bullet list-->
     * bullet
     * another bullet
     * more bullets

<!--Example for Numbered list-->
### 2.2.4 Numbered list
1. First point
2. Second point
3. Third point
<!--Example for Numbered list-->
    1. First point
    2. Second point
    3. Third point


<!--Example text with equotation-->
### 2.2.5 Equotation
If x=2 then it's a relatively small x.

<!--Example for inline code-->
### 2.2.6 Inline code
If you specify `x=2;` then your program will substitute 2 for x.
<!--Example for inline code-->
    If you specify `x=2;` then your program will substitute 2 for x.

<!--A block of code-->
### 2.2.7 Block of code

Here comes a codeblock:
```
x=2;
y=7;
z=x+y;
```

<!--Example for Table-->
### 2.2.8 Table

| header      | another header      |
| ----------- | ------------------- |
| row content | another row content |
| row content | another row content |
| row content | another row content |

<!--Example for Table-->
    | header      | another header      |
    | ----------- | ------------------- |
    | row content | another row content |
    | row content | another row content |
    | row content | another row content |

Paragraph after table

## 2.3 Images  

<!--Example for Images-->
![Text to display if no image](/assets/images/Photo.jpg)
<!--Example for Images-->
    ![Text to display if no image](/assets/images/Photo.jpg)

## 2.4 Links to other source  

<!--Example for links-->
[Weather](http://meteo.pl)

    [Weather](http://meteo.pl)

[Validator](https://validator.w3.org/nu/#textare)

    [Validator](https://validator.w3.org/nu/#textare)

Example for linking to another file.  
**Note:** Both files must be in the same folder.  
[Reference](Test.md)

    [Reference](Test.md)

## 2.5 Variables

## Variables
{: .no_toc}
1. first
2. second
3. third
<!--Example for links-->
    # Variables
    1. first
    2. second
    3. third

## 2.6 Helpful links

[Markdown cheatsheet](./PDF/markdown-cheatsheet.pdf)

[Markdown specifications](https://daringfireball.net/projects/markdown/)

[Markdown tutorial](https://commonmark.org/help/tutorial/index.html)

[Dialects of Markdown](https://sodocumentation.net/markdown/topic/1865/dialects-flavours)

[Visual Studio Code extensions for Markdown](https://github.com/mundimark/awesome-markdown)

[Visual Studio Code – useful options](Visual_Studio_Code–useful_options.md)

To instal Visual Studio Code go to:  

[VS Code installation instructions](Installation_instruction_for_Visual_Studio_Code_software.md)


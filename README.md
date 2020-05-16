# Markdown
Markdown is a lightweight and easy-to-use syntax for styling all forms of writing.

## What is Markdown?
[Markdown][Markdown] is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *. 

 Markdown is very popular to write README's on Github. So, I've given you a tutorial of the markdown.

# Syntax guide

You can find documantation and a complete explanation of Markdown's syntex [here][Markdown].

# Contents
- [Headings](#Headings)
- [Emphasis](#Emphasis)
    - [Bold](#Bold)
    - [Italic](#Italic)
    - [Strikethrough](#Strikethrough)
- [Images](#Images)
- [Links](#Links)
- [Paragraphs](#Paragraphs)
- [BlockQuotes](#BlockQuotes)
- [Lists](#Lists)
    - [Ordered Lists](#Ordered-Lists)
    - [Unordered Lists](#Unordered-Lists)
- [Code](#Code)
- [Syntax highlighting or Multiline code](Syntax-highlighting-or-Multiline-code)
- [Tables](#Tables)
- [Horizontal Rules](#Horizontal-Rules)


## Headings
You can create headings by prefixing with a # (hash mark)

# Heading 1 
    Syntex: 
        # Heading 1
            or
        =====
## Heading 2 
    Syntex:
        ## Heading 2
            or
        ----
### Heading 3
    Syntex:
        ### Heading 3
 
#### Heading 4
    Syntex:
        #### Heading 4

##### Heading 5
    Syntex:
        ##### Heading 5
 
###### Heading 6
    Syntex:
        ###### Heading 6

## Emphasis

### Bold
You can make any text bold by adding double asterisks (*) or double underscores(_).
    
    Syntex:

        **Bold**

        __Bold__

Example:

**This text will be bold**

__This will also be bold__

### Italic
You can make any text italic by adding asterisk (*) or underscore(_).

    Syntex:

        *Italic*

        _Italic_

Example:

*This text will be italic*

_This will also be italic_

### Bold and Italic
Even you can combine both them.

    Syntex:
        You **can** combine them_

Example:

_You **can** combine them_

### Strikethrough

Markdown supports strikethrough by wrapping text in `~~`:

    Syntex:
        ~~This text is strikethrough.~~

Example:

~~This text is strikethrough.~~

## Images

![Alt text](https://github.com/dcurtis/markdown-mark/blob/master/png/208x128-solid.png)

    Syntex:

	![Alt text](https://github.com/dcurtis/markdown-mark/blob/master/png/208x128-solid.png)	

## Links
Markdown supports inline and reference links.

### inline links
To create an inline link, use this syntax:

	[ Text for the link ](URL)

Example:

This is inline [link](www.durgeshsamariya.com).


### reference links
Reference links use square brackts insted of paranthesis.

    Syntex:
        This is [reference][reference-link] link example.

Example:

This is [reference][reference-link] link example.

You can define your link label anywhere in the document, usually at the bottom of the file, as:

	[reference-link]: http://example.com/  "Optional Title Here"

## Paragraphs

A paragraph is one or more consecutive lines of text separated by one or more.

    Syntex:
        This is paragramph one.

        This is paragraph two.

Example:

This is paragraph one.

This is paragraph two.

## BlockQuotes
Markdown uses > (greater than) character for blockquoting.

    Syntex:
        > This is quote.

Example:

> This is quote. 

> Learn from yesterday, live for today, hope for tomorrow. – Albert Einstein

## Lists
Markdown supports ordered (numbered) and unordered (bulleted) lists.

### Ordered Lists

Ordered lists require a numeric character followed by a . (period).

    Syntex:
		1. Item one
		2. Item two 
		3. Item three

Example
1. Item one
2. Item two 
3. Item three

### Unordered Lists

Form bulleted lists with any of * (asterisk), + (plus), or - (dash). You can one or any or mix of these to form a list:

    Syntex:
        * Item one 
        + Item two
        - Item three


* Item one 
+ Item two
- Item three


Lists can be embedded in lists.
    
    Syntex:
        * Item one
        + Item two
	        * Sub item one
	        * Sub item two	
        - Item three
	        1. Sub item one
		        1. sub sub item 1 
		        2. sub sub item 2
	        2. Sub item two 
	            * sub sub one
		        * sub sub two
	        3. Sub item three

Example:

* Item one 
+ Item two
	* Sub item one
	* Sub item two	
- Item three
	1. Sub item one
		1. sub sub item 1 
		2. sub sub item 2
	2. Sub item two 
	    * sub sub one
		* sub sub two
	3. Sub item three

## Code
To indicate a span of code, wrap it with `` ` `` (backtick).

    Syntex:
        `print("This is Markdown demo.")`

Example:

`print("This is Markdown demo.")`

##  Syntax highlighting or Multiline code
For indicating multiple line code spam, wrap code with `` ``` ``(three backticks)

    Syntex:
        ```
            Code line 1
            Code line 2
            Code line 3
        ```

Example:
```
for i in range(10):
    print(i)
```

## Tables

In Markdown you can create table using the - (dash) and the | (pipe) symbols. The first line contains column headers. Separate columns with the pipe symbol. The  second line must be a mandatory separator line between the headers and the content. Subsequent lines are table rows. Columns are always separated by the pipe (|) character.

    Syntex:

	    Header One  | Header Two
	    ------------- | -------------
	    Cell Content  | Cell Content
	    Cell Content  | Cell Content

Example:

| Header One | Header Two |
------------- | -------------
| Cell Content  | Cell Content |
| Cell Content  | Cell Content |

## Horizontal Rules

You can create horizontol rule with any of the following codes:

    Syntex:
        * * *
        ***
    	- - - 
    	---

Example:

Line 1
* * *

Line 2
***

Line 3
- - -

Line 4
___


[Markdown]: https://daringfireball.net/projects/markdown/
[reference-link]: https://durgeshsamariya.com "Durgesh Samariya"
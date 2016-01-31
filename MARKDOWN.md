# Markdown Cheatsheet

https://gist.github.com/philipp-r/8fa32482e9a73003acc7

## Headings

    # H1
    ## H2
    ### H3
    #### H4
    ##### H5
	###### H6

## Emphasis

    Emphasis, aka italics, with *asterisks* or _underscores_.
    Strong emphasis, aka bold, with **asterisks** or __underscores__.
    Combined emphasis with **asterisks and _underscores_**.
    Strikethrough uses two tildes. ~~Scratch this.~~


## Lists

    1. First ordered list item
    2. Another item
    ⋅⋅* Unordered sub-list. 
    1. Actual numbers don't matter, just that it's a number
    ⋅⋅1. Ordered sub-list
    4. And another item.
    
    ⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).
    
    ⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
    ⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
    ⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)
    
    * Unordered list can use asterisks
    - Or minuses
    + Or pluses


## Links

    [I'm an inline-style link](https://www.google.com)
    [I'm an inline-style link with title](https://www.google.com "Google's Homepage")
    URLs and URLs in angle brackets will automatically get turned into links. 
    http://www.example.com or <http://www.example.com>

## Images

    ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

## Code

    Inline `code` has `back-ticks around` it.

        Code blocks are indented with four spaces

## Tables

    Colons can be used to align columns.
    
    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |
    
    There must be at least 3 dashes separating each header cell.
    The outer pipes (|) are optional, and you don't need to make the 
    raw Markdown line up prettily. You can also use inline Markdown.
    
    Markdown | Less | Pretty
    --- | --- | ---
    *Still* | `renders` | **nicely**
    1 | 2 | 3

## Quotes

    > This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

## Horizontal Rule

    Three or more Hyphens    
    ---
    

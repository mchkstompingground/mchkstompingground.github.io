# Some essential MARKDOWN symbols(punctuation-based) you need to know

## HEADER LEVELS
`# header level 1` 
# header level 1 

OR
 
`header level 1`   
`==============`  
header level 1   
==============
`## header level 2`
## header level 2 
 
OR
 
`header level 2`   
`--------------`  
header level 2    
--------------
`### header level 3`
### header level 3 
`#### header level 4`
#### header level 4 
`##### header level 5`
##### header level 5 
`###### header level 6`
###### header level 6 

## FONT EMPHASIS
whole word: emphasis(i.e. italic) & strong emphasis(i.e. bold)  
`_italic_`  _italic_  
`__bold__`  __bold__ 

part of a word: emphasis(i.e. italic) & strong emphasis(i.e. bold)  
`i*tali*c`  i*tali*c  
`b**ol**d`  b**ol**d 

## LINE OR PARAGRAPH WRAPPING
This is a line.                      <= two spaces after end of line (preferred)  
This is the second line.

   or

This is a line.\\\                    <== two back slashes after end of line  
This is the second line.

(N.B. One space / a return is not sufficient. At least two spaces or two back slashes are needed 
      to make another line.)

This is a paragraph.                 <== insert one blank line in order to make another paragraph

This is the second paragraph.

## BLOCKQUOTE
```
This is a famous quote:
> An apple a day keeps the doctor away.
```
This is a famous quote:
> An apple a day keeps the doctor away.


## PREFORMATTED CODE (INLINE)
Just embrace the code with a pair of backticks, e.g.  
```
This is an `*emphasis*` text.
```  
This is an `*emphasis*` text.

## PREFORMATTED CODE (BLOCK)
You must insert four spaces or a TAB as follows:

```
	<a>Hello World</a>	
	<ol>List
		<li>Item 1</li>
		<li>Item 2</li>
	</ol>	
	<div>Hey Judy!</div>
```

	<a>Hello World</a>	
	<ol>List
		<li>Item 1</li>
		<li>Item 2</li>
	</ol>	
	<div>Hey Judy!</div>

## CODE WITH SPECIFIC STYLING (BLOCK)
e.g. for C, the code needs to be inserted between \```c and \``` in order to produce appropriate highlighting:

```c
#include <stdio.h>

int main(void) {
	printf("Hello C!\n");
	return 0;
}
```

## HYPERLINK
```
This is a [guide](http://abc.com) to markdown.
```  
This is a [guide](http://abc.com) to markdown.



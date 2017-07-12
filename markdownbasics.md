## Essential MARKDOWN symbols (punctuation-based) you need to know

## __HEADER LEVELS 1 to 6__
---

    # header level 1

# header level 1 

OR

    header level 1   
    ==============

header level 1   
==============

    ## header level 2

## header level 2 
 
OR
 
    header level 2 
    --------------

header level 2
--------------

    ### header level 3

### header level 3

    #### header level 4

#### header level 4

    ##### header level 5

##### header level 5

    ###### header level 6

###### header level 6

## __FONT EMPHASIS__
---

Whole word: emphasis(i.e. italic) & strong emphasis(i.e. bold) : 
 
`_emphasis_`  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_emphasis_  
`__strong emphasis__`  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;__strong emphasis__ 

Part of a word: emphasis(i.e. italic) & strong emphasis(i.e. bold) :  

`em*pha*sis`  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;em*pha*sis  
`st**rong** em**pha**sis`&nbsp;st**rong** em**pha**sis 

## __LINE OR PARAGRAPH WRAPPING__
---

This is a line. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<= There are __two spaces__ at the end of the line  
This is the second line.

or

This is a line.\\\ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<= There are __two backslashes__ at the end of the line  
This is the second line.

*(N.B. One space or one backslash is not sufficient. At least two spaces or two backslashes are needed to make another line.)*

This is a paragraph. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<= Insert **one blank line after the paragraph** in order to make another paragraph

This is the second paragraph.

## __BLOCKQUOTE__
---

    This is a famous quote:
    > An apple a day keeps the doctor away.

This is a famous quote:

> An apple a day keeps the doctor away.


## __PREFORMATTED CODE (INLINE)__
---

Just embrace the code with __a pair of backticks__, e.g.

    This is an `*emphasis*` text.

This is an `*emphasis*` text.

## __PREFORMATTED CODE (BLOCK)__
---

You must insert __four spaces__ or __a tab__ as follows:

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

## __CODE WITH SPECIFIC STYLING (BLOCK)__
---

e.g. for C, the code needs to be arranged as follows:

	```c
	#include <stdio.h>

	int main(void) {
  	  printf("Hello C!\n");
  	  return 0;
	}
	```

```c
#include <stdio.h>

int main(void) {
  printf("Hello C!\n");
  return 0;
}
```

in order to produce the corresponding highlighting effects.
## __HYPERLINK__
---

    This is a [guide](http://abc.com) to markdown.

This is a [guide](http://abc.com) to markdown.



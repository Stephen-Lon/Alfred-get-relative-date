# Alfred-get-relative-date
An Alfred workflow to get a date relative to today's date
# Usage

This simple workflow calculates a date relative to today's date, displays it in a dialog box and offers the option of copying it to the clipboard. You type the keyword `reldat` followed by <space> and then the relevant date arithmetic.

There is only a very limited check on the validity of the input (it will warn you if you fail to capitalise "M" or try to use time arithmetic). It will not complain if you leave the track completely and use other letters but you won't get a meaningful result. 😀 
The input should be in this format (using the keyword reldat):  

reldat +15D or reldat +15d  
reldat -1Y -2M or reldat -1y -2M  
reldat +3M -2D or reldat +3M -2d  
etc.  

See [this Alfred help page](https://www.alfredapp.com/help/workflows/advanced/placeholders/) for more on date arithmetic.

The workflow has no dependency on any scripting language and simply uses Alfred functions.

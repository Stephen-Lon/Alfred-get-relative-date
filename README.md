# Alfred-get-relative-date
An Alfred workflow to get a date relative to today's date
# Usage

This simple workflow calculates a date relative to today's date, displays it in a dialog box and offers the option of copying it to the clipboard. You type the keyword `reldat` followed by <space> and then the relevant date arithmetic.

There is no check on the validity of the input which should be in this format (using the keyword `reldat`):

`reldat +15D`
`reldat -1Y -2M`
`reldat +3M +2D`

etc.

See [this Alfred help page](https://www.alfredapp.com/help/workflows/advanced/placeholders/) for more on date arithmetic.

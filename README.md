This repo is a clone of the existing latex parser for moin moin, and a place to store some changes I commonly find myself making.

Original parser/code stores here:

http://moinmo.in/ParserMarket/latex

http://johannes.sipsolutions.net/Projects/new-moinmoin-latex

Changes:

* added save_source_as_attachment flag; setting this flag will now add the latex source file as an attachment to the current page, besides the generated .png files. Try using this as the format flag for your page:

   #format latex save_source_as_attachment

This code is available under the GNU GPL


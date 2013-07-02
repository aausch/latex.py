(mostly courtesy of Bernhard Kast)

Requirements:
LaTeX (debian package tetex-bin)
UTF-8 support files for LaTeX (debian package latex-ucs)
dvipng http://sourceforge.net/projects/dvipng (debian package dvipng)
Actual Install:
get the parser code (see code section) (use raw view) and save it as latex.py in your WikiPath/plugin/parser http://johannes.sipsolutions.net/Projects/new-moinmoin-latex/parser?action=raw
get the macro code (see code section) and save it as latex.py in yourWikiPath/plugin/macro http://johannes.sipsolutions.net/Projects/new-moinmoin-latex/macro?action=raw
activate AttachFile in your wikiconfig.py (allowed_actions = ['AttachFile']) (if not activated already)
test if it works, to do this copy this code <<latex(\usepackage{dsfont} % $$\mathds{C}$$)>> into your page and when you get a freaking "" it works 
Setting it as default: add default_markup = "inline_latex" to your config.
 Beware that when you have many equations on a page, the browser has to make a request to the wiki for each page. This can trigger surge protection so you may need to raise the limits.

Another set of installation instructions can be found at http://wiki.vislab.usyd.edu.au/moin.cgi/moinmoin-LaTeX

LibreOffice translations
=========================

In LibreOffice 5, 5000 german code comments are still untranslated and block development. 

Here I started translating them. Please fork and help out.

Format
--------

1. For the output to be machine-processable, I add "    -> " after the line, before the translation::

	sw/source/filter/ww8/ww8struc.hxx:534: hiermit wird weitergearbeitet (entspricht weitestgehend dem Ver8-Format
	    -> with this we continue (largely matches the Ver8-format

2. Although the original german text may be multiple lines, I make the english 
   translation a single line, so that it can be machine-processed.

3. In [], I put comments about the translation. 
   for example if words are ambiguous, I offer alternative words or an explanation.

I started at the bottom, just in case someone else starts at the top.



How to help
------------
Fork, translate, send pull requests! I will merge any pull requests immediately.


Links: 
-----------

* https://people.gnome.org/~michael/blog/2015-08-05-under-the-hood-5-0.html
* https://people.gnome.org/~michael/data/2015-08-01-german-comments.txt



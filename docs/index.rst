==============
Mikado Publish
==============

Tooling for producing books for self publishing
-----------------------------------------------

Some rough ill-thought out notes from around the web


Notes
-----

I want to start with `.rst` files and using (probably) the Sphinx
documentation generator, or just plain old `docutils` if sphinx gets
in the way, produce nice configured html (for reading), latex and
.mobi (no point pretending people buy to read on anything other than
kindle)

The process
-----------

* Writing and typesetting / designing the book are co-dependant
* 50% of the effort should be marketing (!)
* even if you aren't expecting people to buy it you still want a readership
* so promote it.

My marketing plan

* a landing page with mailchimp email list
* Hacker News
* tell all my friends
* free copies instead of business cards


https://kdp.amazon.com/en_US/help/topic/G201723070

Differences in latex and what sphinx puts out
---------------------------------------------

What is this odd document class thing???


Basic Latex config
------------------
https://www.andy-roberts.net/writing/latex

Use the `memoir` document class.
http://texdoc.net/texmf-dist/doc/latex/memoir/memman.pdf
http://zeeba.tv/introduction-to-memoir/

Building .mobi from sphinx:
---------------------------

https://github.com/EronHennessey/sphinx-mobi-builder
(just follow the instructions, dont use the tool he has deprecated it)

set config fixes as described, then generate epub from sphinx.
use kindlegen command line tool to convert from epub to mobi
then thats basically it !
Use the (mac win) kindle viewer tool to check the output manually

building epubs
--------------
http://www.sphinx-doc.org/en/master/faq.html#epub-faq


Config for KDP
--------------
https://kdp.amazon.com/en_US/help/topic/G201834180



Multiple sites
--------------

I expect to use paul-brian.com as the "top owner" site for all
my other products - see https://www.dominicholland.co.uk/ as a good example?




# Under the hood


## Your site's stack

This site uses the static site generator and documentation site builder 
[sphinx](https://www.sphinx-doc.org/en/master/index.html). 

Sphinx can also automatically generate documentation website from example code for a library and the underlying documentation in the package. It is focused on python but has [other language support](https://www.sphinx-doc.org/en/master/tutorial/describing-code.html).  A popular way to do this in Python is with [autodoc](https://www.sphinx-doc.org/en/master/usage/extensions/autodoc.html), other languages have other exensions, for example [matlabdomain adds MATLAB support](https://github.com/sphinx-contrib/matlabdomain).  


## For the workshop

The shorturls eg `drsmb.co/nsbe50` are hosted in a [repo, drsmb-co.github.io](https://github.com/drsmb-co/drsmb-co.github.io) that is linked to my custom domain `drsmb.co`.  It builds from a yaml file to the html site using a package [urlfwd](https://github.com/brownsarahm/urlfwd) that I made called by a
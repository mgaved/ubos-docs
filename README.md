UBOS website and documentation
==============================

On-line at [ubos.net](https://ubos.net/)

* The main site is created with [Jekyll](http://jekyllrb.com/). Sources are in directory `jekyll`.
* The /docsXXX subdirectories are created with [Sphinx](http://sphinx-doc.org/). Sources are in directory `sphinx`.

Branch `yellow` has the documentation for the `yellow` release channel; branch `master` has
it for the `green` release channel.

Note that the Sphinx parts use the CSS generated by Jekyll.

Found errors, omissions, improvements? Submit a pull request!

To re-generate the site:

```
   make clean all
```

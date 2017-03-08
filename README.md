# pdir2

Have you ever dreamed of a better output of `dir()`? I do. So I created this.

![](images/presentation.gif)

## Features
* Attributes are grouped by types/functionalities, with beautiful colors.

* Support all platforms including Windows(Thanks to [colorama](https://github.com/tartley/colorama)).

* The return value of `pdir()` can still be used as a list of names.

* You can search for certain names with `.s()` or `.search()`:  

  ![](images/search.gif)


## Install
(NOTE: It's not on pypi yet so now you have to install using setup.py.
 I'll upload it asap.)
```
pip install pdir2
```
About the name. I wanted to call it `pdir`, but there's already one with this
name on pypi. Mine is better, of course.

## Testing
Simply run `pytest`, or use `tox` if you like.

## Roadmap
- [] lint
- [] config color
- [] colorful docstring
"""

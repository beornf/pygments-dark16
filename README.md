Installation:
=============

Using PyPI and pip:

    pip install pygments-dark16

Manual installation:

    git clone git://github.com/beornf/pygments-dark16.git
    cd pygments-dark16
    python setup.py install


Usage example:
==============

    >>> from pygments.formatters import HtmlFormatter
    >>> HtmlFormatter(style='dark16').style
    <class 'pygments_dark16.Base16DarkStyle'>


Please read the [official documentation][pygments] for further information
on the usage of pygment styles.


[pygments]: http://pygments.org/docs/

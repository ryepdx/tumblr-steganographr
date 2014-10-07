tumblr-steganographr
=====================

A Python script that lets you hide and retrieve encrypted data in Tumblr posts.

Uses the [Python Imaging Library](http://www.pythonware.com/products/pil/), which is available for easy installation on the [Python Package Index](https://pypi.python.org/pypi/PIL) by the likes of [`easy_install`](https://pypi.python.org/pypi/setuptools#installation-instructions) and (my personal preference) [`pip`](https://pip.pypa.io/en/latest/installing.html).

## Installing PIL (prerequisite)

**Using `pip`:**

    $ pip install PIL --allow-unverified PIL --allow-all-external

If you're running a \*nix system like mine, you might need to prepend `sudo` to that command.

**Using `easy_install`:**

    $ easy_install --find-links http://www.pythonware.com/products/pil/ Imaging

(Thanks to [athena geek](http://athenageek.wordpress.com/2009/06/09/easy_install-pil-not-so-easy/) for that recipe.)

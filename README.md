tumblr-steganographr
=====================

A Python script that lets you hide and retrieve encrypted data in Tumblr posts. It uses NaCl, AES, and simple LSB steganography to achieve its goals. In theory, this would allow for the development of an ad-hoc social network on top of Tumblr.

Uses the [Python Imaging Library](http://www.pythonware.com/products/pil/), which is available for easy installation on the [Python Package Index](https://pypi.python.org/pypi/PIL) by the likes of [`easy_install`](https://pypi.python.org/pypi/setuptools#installation-instructions) and (my personal preference) [`pip`](https://pip.pypa.io/en/latest/installing.html).

## Installing prerequisites

**Using `pip`:**

    $ pip install PIL --allow-unverified PIL --allow-all-external
    $ pip install simple-crypt pytumblr pynacl

If you're running a \*nix system like mine, you might need to prepend `sudo` to those commands.

**Using `easy_install`:**

    $ easy_install --find-links http://www.pythonware.com/products/pil/ Imaging

(Thanks to [athena geek](http://athenageek.wordpress.com/2009/06/09/easy_install-pil-not-so-easy/) for that recipe.)

## For Developers

`tumblr-steganographr` uses [`sniffer`](https://pypi.python.org/pypi/sniffer) and [`nose`](https://pypi.python.org/pypi/nose/1.3.4) for running tests, so you will need those installed in order to contribute to this project.

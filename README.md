Emacs Url Shortener
=====================

  this package can convert long url to tiny url and expand tiny url to long url
  ,support:

  * bit.ly
  * goo.gl
  * dwz.cn
  * 126.am

Installation
------------

ELPA packages are available on Melpa. Alternatively, download
the latest release or clone the repository, and install
url-shortener.el with <kbd> M-x package-install-from-file </kbd>.

Configuration
------------

If you want to use the service provided by bit.ly, you should get an
access token from https://bitly.com/a/oauth_apps, then append
following code to your .emacs

```emacs-lisp
(setq bitly-access-token "your access token")
```

Usage
------------

there are some commands to do url shorten and expand:

* <kbd> M-x goo-url-shorten </kbd>
* <kbd> M-x goo-url-expand </kbd>
* <kbd> M-x bitly-url-shorten </kbd>
* <kbd> M-x bitly-url-expand </kbd>
* <kbd> M-x dwz-url-shorten </kbd>
* <kbd> M-x dwz-url-expand </kbd>
* <kbd> M-x 126am-url-shorten </kbd>
* <kbd> M-x 126am-url-expand </kbd>

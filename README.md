[![MELPA](http://melpa.org/packages/url-shortener-badge.svg)](http://melpa.org/#/url-shortener)
<!-- [![MELPA Stable](http://stable.melpa.org/packages/url-shortener-badge.svg)](http://stable.melpa.org/#/url-shortener) -->
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

if you use goo.gl, you also need an api key, you can get from https://developers.google.com/url-shortener/v1/getting_started#APIKey, then append `(setq goo-api-key "you api key")` to your dotemacas.
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

## License

Copyright (C) 2013-2017 Yu Yang

Author: Yu Yang <yyangplus@NOSPAM.gmail.com>
Keywords: url shorten expand

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.


## Original README

Excerpt from the README available at https://github.com/jrconlin/oauthsimple

### Name

OAuthSimple - a very simple OAuth 1.0 signed request generator

### Synopsis

See source comments for usage examples

### Description

OAuthSimple aids in building valid OAuth 1.0 requests. It does not perform
token requests by itself, however you can use it to build the request calls.

I've tried to build the library to be fairly common so that if you're familiar
with how it works in one language, you can use it in any other. Right now the
following languages are supported: PHP, Javascript, Perl, Python. I'd love to add additional
languages and may do so in the future. (I'd be happy to accept contributions,
hint, hint.)

Guido Schlabitz has provided a useful example for how to use
OAuthSimple to connect to Google
http://github.com/jrconlin/oauthsimple/blob/master/php/example.php

OAuthSimple accepts arguments in a variety of formats and returns a structure
containing valid elements, including a fully structured URL, an Authorization
header and the signature value. You should only use either the Authorization
Header (as per the spec), or the fully structured URL. (Again, see source
comments for appropriate usage.)

OAuth Developers may be interested in my OAuthTestPage at:
http://jrconlin.github.com/OAuthTestPage/

This will display OAuth1a valid elements and values so you can verify things are working correctly.

### License

Code is released under a BSD licence.


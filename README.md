# ReCaptcha

The ReCaptcha library is a PHP library that allows the easy use of the ReCaptcha service to prevent spam on user-facing forms.

However, I found the ReCaptcha library fairly horrific in that it was functional, and unable to be auto-loaded by common frameworks.

Therefore this fork aims to be auto-loadable and to provide a more convenient interface for developers

## Use

Same functions as before, except instead of them starting with recaptcha_ just instanciate a new ReCaptcha_Lib object and call the method names on that (no recaptcha_)

## License

See LICENSE file

## Original Readme follows

reCAPTCHA README
================

The reCAPTCHA PHP Lirary helps you use the reCAPTCHA API. Documentation
for this library can be found at

	http://recaptcha.net/plugins/php

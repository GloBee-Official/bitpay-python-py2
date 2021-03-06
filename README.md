# GloBee Library for Python 2

Powerful, flexible, lightweight interface to the cryptographically secure GloBee Bitcoin & Altcoin Payment Gateway API.

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://raw.githubusercontent.com/bitpay/bitpay-python-py2/master/LICENSE.txt)
[![Travis](https://img.shields.io/travis/bitpay/bitpay-python-py2.svg?style=flat-square)](https://travis-ci.org/bitpay/bitpay-python-py2)
[![Latest Version](https://pypip.in/version/bitpay_py2/badge.svg?style=flat-square)](https://pypi.python.org/pypi/bitpay-py2/)
[![Supported Python versions](https://pypip.in/py_versions/bitpay_py2/badge.svg?style=flat-square)](https://pypi.python.org/pypi/bitpay-py2/)
[![Code Climate](https://img.shields.io/codeclimate/github/bitpay/bitpay-python-py2.svg?style=flat-square)](https://codeclimate.com/github/bitpay/bitpay-python-py2)
[![Scrutinizer](https://img.shields.io/scrutinizer/g/bitpay/bitpay-python-py2.svg?style=flat-square)](https://scrutinizer-ci.com/g/bitpay/bitpay-python-py2/)
[![Coveralls](https://img.shields.io/coveralls/bitpay/bitpay-python-py2.svg?style=flat-square)](https://coveralls.io/r/bitpay/bitpay-python-py2)

This library is only compatible with Python 2. If you're using Python 3.x, please use our separate [bitpay-python](https://github.com/GloBee-Official/bitpay-python) library.

## Getting Started
To get up and running with this library quickly, see these getting started guides:
* https://github.com/GloBee-Official/bitpay-python-py2/blob/master/GUIDE.md
* https://support.bitpay.com/hc/en-us/articles/115003001203-How-do-I-configure-and-use-the-BitPay-Python-Library-
* https://bitpay.com/docs/testing

## API Documentation

API Documentation is available on the [GloBee site](https://globee.com/api-docs).

## Running the Tests

Before running the behavior tests, you will need a test.globee.com account and you will need to set the local constants.

To set constants:
    > source tasks/set_constants.sh "https://test.globee.com" your@email yourpassword

To run unit tests:
    > nosetests

To run behavior tests:
    > behave

## Found a bug?

Let us know! Send a pull request or a patch. Questions? Ask! We're here to help. We will respond to all filed issues.

**GloBee Support:**

* [GitHub Issues](https://github.com/GloBee-Official/bitpay-python-py2/issues)
  * Open an issue if you are having issues with this library
* [Support](https://globee.com)
  * GloBee merchant support documentation

Sometimes a download can become corrupted for various reasons.  However, you can verify that the release package you downloaded is correct by checking the md5 checksum "fingerprint" of your download against the md5 checksum value shown on the Releases page.  Even the smallest change in the downloaded release package will cause a different value to be shown!
  * If you are using Windows, you can download a checksum verifier tool and instructions directly from Microsoft here: http://www.microsoft.com/en-us/download/details.aspx?id=11533
  * If you are using Linux or OS X, you already have the software installed on your system.
    * On Linux systems use the md5sum program.  For example:
      * md5sum filename
    * On OS X use the md5 program.  For example:
      * md5 filename

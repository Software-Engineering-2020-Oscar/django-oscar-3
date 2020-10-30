# Contributions for Django-Oscar project :smile:

<p align = "center">
  <img src = "https://github.com/NhutNguyen236/django-oscar-2/blob/master/docs/images/logos/oscar.png"/>
</p>

# Domain-driven e-commerce for Django

Oscar is an e-commerce framework for Django designed for building domain-driven
sites.  It is structured such that any part of the core functionality can be
customised to suit the needs of your project.  This allows a wide range of
e-commerce requirements to be handled, from large-scale B2C sites to complex B2B
sites rich in domain-specific business logic.

# Caution - must read :thinking:
* Please mark this as we are junior from TDTU and this repo is consumed as a fair-used project to submit to our subject Software Engineering only, which means there will be no further application in the future.
* If you want to re-use, please contact me through my email which is provided above. 
* If you're trying to bypass the rules, you know what will come. :relieved:

Contents:

<p><img src = "https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/oscarcommerce.thumb.png"/><img src = "https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/readthedocs.thumb.png"/></p>

Further reading:

* [`Official homepage`](http://oscarcommerce.com)
* [`Sandbox site`](https://latest.oscarcommerce.com)
* [`Our main site using sandbox`](https://www.giadungthongminhsg.com)
* [`Documentation`](https://django-oscar.readthedocs.io/en/stable/) on the excellent [readthedocs.org`](http://readthedocs.org)
* [`Docker image`](https://hub.docker.com/r/oscarcommerce/django-oscar-sandbox/)
* [`django-oscar group`](https://groups.google.com/forum/?fromgroups#!forum/django-oscar) - mailing list for questions and announcements
* [`django-oscar-jobs group`](https://groups.google.com/forum/?fromgroups#!forum/django-oscar-jobs) - mailing list for job offers
* [`Continuous integration homepage`](http://travis-ci.org/#!/django-oscar/django-oscar) on [`travis-ci.org`](http://travis-ci.org/)
* [`Twitter account for news and updates`](https://twitter.com/#!/django_oscar)
* #django-oscar on Freenode (community-run IRC channel) with [`public logs`](https://botbot.me/freenode/django-oscar/)
* [`Slack`](https://slack.oscarcommerce.com/)
* [`PyPI page`](https://pypi.python.org/pypi/django-oscar/)
* [`Transifex project`](https://www.transifex.com/projects/p/django-oscar/) - translating Oscar made easy

Continuous integration status:

[![Foo](https://travis-ci.org/django-oscar/django-oscar.svg?branch=master)](https://travis-ci.org/django-oscar/django-oscar)
[![Foo](http://codecov.io/github/django-oscar/django-oscar/coverage.svg?branch=master)](http://codecov.io/github/django-oscar/django-oscar?branch=master)
[![Foo](https://requires.io/github/django-oscar/django-oscar/requirements.svg?branch=master)](https://requires.io/github/django-oscar/django-oscar/requirements/?branch=master)
[![Foo](https://img.shields.io/pypi/v/django-oscar.svg)](https://pypi.python.org/pypi/django-oscar/)
[![Foo](https://readthedocs.org/projects/django-oscar/badge/)](https://readthedocs.org/projects/django-oscar/)

### Core team of Oscar:

* [`David Winterbottom`](https://github.com/codeinthehole)
* [`Maik Hoepfel`](https://github.com/maikhoepfel)
* [`Markus Bertheau`](https://github.com/mbertheau)
* [`Michael van Tellingen`](https://github.com/mvantellingen) 
* [`Alexander Gaevsky`](https://github.com/sasha0)
* [`Samir Shah`](https://github.com/solarissmoke)

### My projetc team:

* [`Dang Duc Vinh`]()
* [`Nguyen Minh Nhut`](https://github.com/NhutNguyen236)
* [`Nguyen Thanh Nguyen`](https://github.com/kiddonguyen)
* [`Vo Lam Duy Thuan`]()
* [`Ha Quan Quan`](https://github.com/Blanc-2308)

Supported versions
------------------

The currently supported versions of Oscar are:

| Version | End of support |
|:-------:|:--------------:|
| 2.1 LTS |   August 2023  |

Supported verions are eligible for fixes for data loss bugs and security issues. Releases designated as
Long-term support (LTS) releases will receive support for an extended period of 3 years from their release date.


# Screenshots

## Sandbox

### Extensions

The following extensions are stable and ready for use:

* [django-oscar-api](https://github.com/django-oscar/django-oscar-api) - RESTful JSON API for django-oscar

* [django-oscar-adyen](https://github.com/django-oscar/django-oscar-adyen) - Integration with the Adyen payment gateway

* [django-oscar-datacash](https://github.com/django-oscar/django-oscar-datacash) - Integration with the [DataCash](http://www.datacash.com/) payment gateway

* [django-oscar-paypal](https://github.com/django-oscar/django-oscar-paypal) - Integration with PayPal.  This currently supports both
  [`Express Checkout`](https://www.paypal.com/uk/cgi-bin/webscr?cmd=_additional-payment-ref-impl1) and [`PayFlow Pro`](https://merchant.paypal.com/us/cgi-bin/?cmd=_render-content&content_ID=merchant/payment_gateway).

* [django-oscar-paymentexpress](https://github.com/django-oscar/django-oscar-paymentexpress)- Integration with the [`Payment Express`](http://www.paymentexpress.com) payment
  gateway

* [django-oscar-accounts](https://github.com/django-oscar/django-oscar-accounts) - Managed accounts (can be used for giftcard
  functionality and loyalty schemes)

* [django-oscar-stores](https://github.com/django-oscar/django-oscar-stores) - Physical stores integration (opening hours, store
  locator etc)

* [django-oscar-eway](https://github.com/snowball-one/django-oscar-eway) - Integration with the [eWay](https://www.eway.com.au) payment gateway.

* [django-oscar-sagepay-direct](https://github.com/django-oscar/django-oscar-sagepay-direct) - Integration with "DIRECT" part of Sagepay's API

* [django_oscar_docdata](https://github.com/django-oscar/django-oscar-docdatac)- Integration with Docdata_ payment gateway.

* [django_oscar_invoices](https://github.com/django-oscar/django-oscar-invoices) - Invoices or receipts generation for the
  Oscar

The following are community-written extensions:

* django-oscar-payments_ - Pluggable payments for Oscar
* django-oscar-recurly_ - Integration with the Recurly payment gateway

* django-oscar-przelewy24_ - Integration with the Przelewy24 payment gateway
* oscar-sagepay_ - Payment integration with Sage Pay

* django-oscar-sofortueberweisung_ - Integration with SOFORT

* django-oscar-support_ - Customer services and ticketing plugin for Oscar

* django-oscar-api-checkout_ - Oscar API Checkout is a layer on top of
  django-oscar and django-oscar-api, adding support for more complex and
  multiple payment options during an API checkout.

* django-oscar-bundles_ - Oscar Bundles adds multi-product bundles to
  django-oscar.

* django-oscar-bluelight_ - `Bluelight Specials`_ is a layer on-top of
  django-oscar that adds support for more complex offers and vouchers,
  including conjunctive and disjunctive compound conditions.

* django-oscar-cch_ - Oscar CCH is a plugin for django-oscar adding support
  for calculating taxes using the Wolters Kluwer `CCH Sales Tax Office`_ SOAP
  API.

* django-oscar-cybersource_ - Oscar CyberSource is a plugin for Oscar API
  Checkout that makes it possible to use
  `CyberSource Secure Acceptance Silent Order Post`_ as an order payment
  method.

* django-oscar-wfrs_ - Oscar WFRS is a plugin for django-oscar-api-checkout_
  that makes it possible to use `Wells Fargo Retail Services`_ as an order
  payment method.

Let us know if you're writing a new one!

.. _django-oscar-unicredit: https://bitbucket.org/marsim/django-oscar-unicredit/
.. _django-oscar-payments: https://github.com/Lacrymology/django-oscar-payments
.. _django-oscar-recurly: https://github.com/mynameisgabe/django-oscar-recurly

.. _django-oscar-przelewy24: https://github.com/kisiel/django-oscar-przelewy24
.. _oscar-sagepay: https://github.com/udox/oscar-sagepay
.. _django-oscar-sofortueberweisung: https://github.com/byteyard/django-oscar-sofortueberweisung

.. _django-oscar-support: https://github.com/SalahAdDin/django-oscar-support
.. _django-oscar-api-checkout: https://github.com/thelabnyc/django-oscar-api-checkout
.. _django-oscar-bundles: https://github.com/thelabnyc/django-oscar-bundles
.. _django-oscar-bluelight: https://github.com/thelabnyc/django-oscar-bluelight
.. _`Bluelight Specials`: https://en.wiktionary.org/wiki/blue-light_special
.. _django-oscar-cch: https://github.com/thelabnyc/django-oscar-cch
.. _`CCH Sales Tax Office`: http://www.salestax.com/solutions/calculation/cch-salestax-office/
.. _django-oscar-cybersource: https://github.com/thelabnyc/django-oscar-cybersource
.. _`CyberSource Secure Acceptance Silent Order Post`: https://www.cybersource.com/products/payment_security/secure_acceptance_silent_order_post/
.. _django-oscar-wfrs: https://github.com/thelabnyc/django-oscar-wfrs
.. _`Wells Fargo Retail Services`: https://retailservices.wellsfargo.com/

Videos
------

Videos with talks about Oscar:

* `An introduction to Django-oscar`_ by `David Winterbottom`_, DjangoCon Europe 2014
* `Oscar and the art of transactional Django applications`_ by `David Winterbottom`_, PyCon PL 2014
* `The Tale of Oscar and the API`_ by `Kees Hink`_, PyGrunn 2017

.. _`An introduction to Django-oscar`: https://youtu.be/o4ol6EzGDSw
.. _`Oscar and the art of transactional Django applications`: https://youtu.be/datKUNTKYz8
.. _`The Tale of Oscar and the API`: https://youtu.be/YPnKoiyGIHM
.. _`Kees Hink`: https://github.com/khink

License
-------

Oscar is released under the permissive `New BSD license`_ (see summary_).

.. _summary: https://tldrlegal.com/license/bsd-3-clause-license-(revised)

.. _`New BSD license`: https://github.com/django-oscar/django-oscar/blob/master/LICENSE

Case studies
------------

Oscar is still in active development but is used in production by a range of
companies, from large multinationals to small, boutique stores. See
http://oscarcommerce.com/cases.html for an overview.

Many more on the way.  If you use Oscar in production, please `let us know`_.

.. _`let us know`: https://github.com/django-oscar/oscarcommerce.com/issues

Looking for commercial support?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you are interested in having an Oscar project built for you, or for
development of an existing Oscar site then please get in touch via `info@oscarcommerce.com`_.

.. _`info@oscarcommerce.com`: mailto:info@oscarcommerce.com

Deployment infor
------------
* Django-Oscar in my case was deployed on Pythonanywhere and the domain name is `giadungthongminhsg.com <https://www.giadungthongminhsg.com/>`_

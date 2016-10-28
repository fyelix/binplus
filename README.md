BIN+
=======

BIN+ is simple api for collection the first 6 digits on a credit card, and is used to identify a few things. It tells the checker where the card was issued and open to public for free checking,
Why check BINs? 

 * Collect metrics on card types
 * Identify internationally issued cards
 * Determine issuing institution
 * Distinguish debit and credit cards

*Current version: [v0.0.1]*

Features
---------------
With our API you just using only the first six digits of any credit card number.

* Determine if a card is a VISA, MASTERCARD, AMERICAN EXPRESS or any other card brand.
* Determine if a card is a Debit card or a Credit card.
* Find the level of the card such as Business, Platinum, Gold etc.
* Detect Prepaid, Gift and Virtual Cards.
* Find which bank has issued the card.
* Find from which country the card was issued.
* Find the issuing contact phone and website of the bank which issued the card.

Getting Started
---------------
We offering basic usage with JSON , XML , CSV (Soon)
### Via JSON

You can basically using our API with JSON response 

``` curl
curl https://bin.plus/api/json/<YOUR BIN>/bin
```

After you've done this, you probably can parsing this response data

### Via a XML

You can basically using our API with XML response 

``` curl
curl https://bin.plus/api/xml/<YOUR BIN>/bin
```

After you've done this, you probably can parsing this response data

### Via a CSV

You can basically using our API with CSV response 

``` curl
curl https://bin.plus/api/csv/<YOUR BIN>/bin
```

After you've done this, you probably can parsing this response data

Misc
====

Inspirations
------------

The following projects have inspired Flatdoc.

 * [Backbone.js] - Jeremy's projects have always adopted this "one page
 documentation" approach which I really love.

 * [Docco] - Jeremy's Docco introduced me to the world of literate programming,
 and side-by-side documentation in general.

 * [Stripe] - Flatdoc took inspiration on the look of their API documentation.

 * [DocumentUp] - This service has the same idea but does a hosted readme 
 parsing approach.

Attributions
------------

[Photo](http://www.flickr.com/photos/doug88888/2953428679/) taken from Flickr,
licensed under Creative Commons.

Acknowledgements
----------------

Â© 2013, 2014, Rico Sta. Cruz. Released under the [MIT 
License](http://www.opensource.org/licenses/mit-license.php).

**Flatdoc** is authored and maintained by [Rico Sta. Cruz][rsc] with help from its 
[contributors][c].

 * [My website](http://ricostacruz.com) (ricostacruz.com)
 * [Github](http://github.com/rstacruz) (@rstacruz)
 * [Twitter](http://twitter.com/rstacruz) (@rstacruz)

[rsc]: http://ricostacruz.com
[c]:   http://github.com/rstacruz/flatdoc/contributors

[GitHub API]: http://github.com/api
[marked]: https://github.com/chjj/marked
[Backbone.js]: http://backbonejs.org
[dox]: https://github.com/visionmedia/dox
[Stripe]: https://stripe.com/docs/api
[Docco]: http://jashkenas.github.com/docco
[GitHub pages]: https://pages.github.com
[fences]:https://help.github.com/articles/github-flavored-markdown#syntax-highlighting
[DocumentUp]: http://documentup.com

[project]: https://github.com/rstacruz/flatdoc
[template]: https://github.com/rstacruz/flatdoc/raw/gh-pages/templates/template.html
[blank]: https://github.com/rstacruz/flatdoc/raw/gh-pages/templates/blank.html
[dist]: https://github.com/rstacruz/flatdoc/tree/gh-pages/v/0.9.0

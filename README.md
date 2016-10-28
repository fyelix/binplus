BIN+
=======

BIN+ is simple api for collection the first 6 digits on a credit card, and is used to identify a few things. It tells the checker where the card was issued and open to public for free checking
Why check BINs? 

 * Collect metrics on card types
 * Identify internationally issued cards
 * Determine issuing institution
 * Distinguish debit and credit cards

*Current version: [v0.9.0][dist]*

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

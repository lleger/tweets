# [@lleger](http://twitter.com/lleger) tweets

## Viewing tweets

The simplest way to use this Twitter archive is through the archive browser interface provided in this file. Just double-click [`index.html`](index.html) from the root folder and you can browse the entire history of Tweets from inside your browser.

## Data

In the [`data`](data) folder, the Twitter archive is present in two formats: JSON and CSV exports by month and year.

* CSV is a generic format that can be imported into many data tools, spreadsheet applications, or consumed simply using a programming language.
* The JSON export contains a full representation of your Tweets as returned by v1.1 of the Twitter API. See https://dev.twitter.com/docs/api/1.1 for more information.
* The JSON export is also used to power the archive browser interface (index.html).
* To consume the export in a generic JSON parser in any language, strip the first and last lines of each file.
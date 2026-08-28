# AlaSQLGS

AlaSQLGS is a Google Apps Script library that brings [AlaSQL.js](http://alasql.org) to Apps Script projects, making it possible to run SQL-like queries against JavaScript data and script-managed resources. It is built on the Google Apps Script runtime and the AlaSQL.js query engine, so it fits naturally into Apps Script workflows while keeping a familiar SQL-style API.

## Tech stack

- [Google Apps Script](https://developers.google.com/apps-script/) runtime
- [AlaSQL.js](http://alasql.org) as the underlying SQL engine
- JavaScript for library usage and integration

## Loading the library

To load AlaSQLGS:

```js
const alasql = AlaSQLGS.load();
```

The library supports lazzy loading.

## Copying the library

A Google Apps Script project for AlaSQL is available [here](https://script.google.com/d/1XWR3NzQW6fINaIaROhzsxXqRREfKXAdbKoATNbpygoune43oCmez1N8U/edit?usp=sharing).

1. Select Overview left pane in the Apps Script IDE.
1. In the upper right corner find the copy icon.

## Samples

[Data and code](https://drive.google.com/drive/folders/1iG34CHDVBIwqG8yOcjJYHl3gx1IsTzOJ?usp=sharing)

## Links

- [agershun/alasql](https://github.com/agershun/alasql)

## License

AlaSQLGS for Google Apps Script is released under the MIT license.

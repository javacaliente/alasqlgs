# AlaSQLGS

AlaSQLGS is a Google Apps Script library that brings [AlaSQL.js](http://alasql.org) to Apps Script projects, making it possible to run SQL-like queries against JavaScript data and script-managed resources. It is built on the Google Apps Script runtime and the AlaSQL.js query engine, so it fits naturally into Apps Script workflows while keeping a familiar SQL-style API.

## Tech stack

- [Google Apps Script](https://developers.google.com/apps-script/) runtime and library system
- [AlaSQL.js](http://alasql.org) as the underlying SQL engine
- JavaScript for scripting, integration, and query execution

### Runtime and compatibility

AlaSQLGS is designed for Google Apps Script projects, so it runs in the Apps Script environment rather than in a standalone browser app or Node.js server. That makes it a good fit for automation, spreadsheet workflows, and scripts that need lightweight query capabilities inside the Google Workspace ecosystem.

### Library packaging

The project is published as an Apps Script library, which means you can add it to an existing Apps Script project without copying the source into your script. After adding the library, you can access it through the provided namespace and use it directly in your code.

### Lazy loading

The library supports lazy loading, so AlaSQL can be initialized only when it is needed instead of immediately on startup. This can help keep Apps Script code leaner and reduce unnecessary work in scripts that only use SQL functionality in certain paths.

### Example use cases

- querying arrays of JavaScript objects in Apps Script
- filtering and transforming data before writing to Sheets
- combining data from Google Sheets, forms, or other Apps Script sources
- building small reporting or data-preparation scripts with SQL-like syntax

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

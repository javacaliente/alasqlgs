# AlaSQLGS

AlaSQLGS is a Google Apps Script library that brings [AlaSQL.js](http://alasql.org) to Apps Script projects. It gives you a SQL-like query engine inside the Google Apps Script runtime, so you can filter, transform, and analyze data using familiar SQL-style syntax without leaving your Apps Script workflow.

It is especially useful when you want to work with arrays of JavaScript objects, data pulled from Google Sheets, or other script-managed data sources and apply queries, joins, and aggregations in code.

## What it is

AlaSQLGS is a wrapper around [AlaSQL.js](http://alasql.org) packaged for [Google Apps Script](https://developers.google.com/apps-script/). It lets you use AlaSQL from Apps Script while keeping the integration lightweight and easy to load into an existing project.

## Tech stack

- [Google Apps Script](https://developers.google.com/apps-script/) runtime and library system
- [AlaSQL.js](http://alasql.org) as the underlying SQL/query engine
- JavaScript for scripting, library integration, and query execution

## How it works

AlaSQLGS exposes AlaSQL through an Apps Script-friendly interface. After loading the library, you can initialize AlaSQL and use it in your scripts.

```js
const alasql = AlaSQLGS.load();
```

Because the project is packaged as an Apps Script library, you can add it to an existing script project instead of copying the full source into your codebase. That makes it easier to share, update, and reuse across Apps Script projects.

The library also supports lazy loading, which means AlaSQL can be initialized only when you actually need it. That can be helpful in scripts where SQL-style processing is only used in certain execution paths.

## Example use cases

- querying arrays of JavaScript objects with SQL-like syntax
- filtering and transforming data before writing it to Google Sheets
- combining or reshaping data from Apps Script sources such as Sheets, Forms, or custom objects
- building lightweight reports and data-preparation scripts
- prototyping data workflows without introducing a separate database layer

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

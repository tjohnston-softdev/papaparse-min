# papaparse-min

Mirror of the [papaparse](https://www.npmjs.com/package/papaparse) package that only contains the minified JavaScript file. That is, without any unnecessary files such as documentation and unit tests. It is good to have those resources available but they're a complete waste of space in a production environment and inflate the package's size. This has been published as a separate package by [@tjohnston-softdev](https://github.com/tjohnston-softdev) for those who only need the minified code but still want to keep their dependencies organized.

---

Parse CSV with JavaScript
========================================

Papa Parse is the [fastest](http://jsperf.com/javascript-csv-parsers/4) in-browser CSV (or delimited text) parser for JavaScript. It is reliable and correct according to [RFC 4180](https://tools.ietf.org/html/rfc4180), and it comes with these features:

- Easy to use
- Parse CSV files directly (local or over the network)
- Fast mode ([is really fast](http://jsperf.com/javascript-csv-parsers/3))
- Stream large files (even via HTTP)
- Reverse parsing (converts JSON to CSV)
- Auto-detect delimiter
- Worker threads to keep your web page reactive
- Header row support
- Pause, resume, abort
- Can convert numbers and booleans to their types
- Optional jQuery integration to get files from `<input type="file">` elements
- One of the only parsers that correctly handles line-breaks and quotations

Papa Parse has **no dependencies** - not even jQuery.

Install
-------

'papaparse-min' is available on [npm](https://www.npmjs.com/package/papaparse-min).  
It can be installed with the following command:

    npm install papaparse-min




Homepage & Demo
----------------

- [Homepage](http://papaparse.com)
- [Demo](http://papaparse.com/demo)
- [Documentation](http://papaparse.com/docs)

The website is hosted on [Github Pages](https://pages.github.com/).

Tests
-----

Download the [original repository](https://github.com/mholt/PapaParse), run `npm install`, then `npm test` to perform the tests.

Contributing
------------

To discuss a new feature or ask a question, open an issue. To fix a bug, submit a pull request to be credited with the [contributors](https://github.com/mholt/PapaParse/graphs/contributors)! Remember, a pull request, *with test*, is best. You may also discuss on Twitter with [#PapaParse](https://twitter.com/search?q=%23PapaParse&src=typd&f=realtime) or directly to me, [@mholt6](https://twitter.com/mholt6).

If you contribute a patch, ensure the tests suite is running correctly. We run continuous integration on each pull request and will not accept a patch that breaks the tests.


---

# Disclaimer

This repository is a mirror of the [papaparse](https://www.npmjs.com/package/papaparse) package for Node JS. It mirrors all versions from 4.0.0 onwards since this is when the package was first published to NPM. The reason this is a completely separate repository and not a fork is to keep the repository as small as possible without any unnecessary files. The original work is licensed under MIT and as such, I claim no personal copyright over this publication. All credit should go to the original developers ([@mholt](https://github.com/mholt), [@pokoli](https://github.com/pokoli), et al.)

This is a only mirror of a package across different versions which have been published to NPM. Minified code cannot be directly maintained but mirrors of newer versions will be published as they are released.

\-[@tjohnston-softdev](https://github.com/tjohnston-softdev)

---


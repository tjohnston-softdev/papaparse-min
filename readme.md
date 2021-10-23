# papaparse-min

Mirror of the [papaparse](https://www.npmjs.com/package/papaparse) package that only contains the minified JavaScript file. That is, without any unnecessary files such as documentation and unit tests. It is good to have those resources available but they're a complete waste of space in a production environment and inflate the package's size. This has been published as a separate package by [@tjohnston-softdev](https://github.com/tjohnston-softdev) for those who only need the minified code but still want to keep their dependencies organized.

---

Parse CSV with JavaScript
========================================

[![mholt on Gratipay](http://img.shields.io/badge/tips-accepted-brightgreen.svg?style=flat)](https://www.gratipay.com/mholt/)

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

Papa Parse has **no dependencies** - not even jQuery.


Homepage & Demo
----------------

- [Homepage](http://papaparse.com)
- [Demo](http://papaparse.com/demo)

To learn how to use Papa Parse:

- [Documentation](http://papaparse.com/docs)


Papa Parse for Node
--------------------

[Rich Harris](https://github.com/Rich-Harris) forked this project to make **[Baby Parse](https://github.com/Rich-Harris/BabyParse)** which runs in Node.js environments.

```bash
$ npm install babyparse
```

[Baby Parse on npm registry](https://www.npmjs.org/package/babyparse)

Use it just like Papa Parse. However:

- Files are not supported; strings only (you can use Node's file facilities to load file contents yourself)
- Some config options are unavailable:
	- worker
	- download (you can use Node's network facilities to download files yourself)
	- encoding
	- chunk

Otherwise, Baby Parse has nearly all the same functionality as Papa Parse 4.0, including the `unparse()` utility.


Get Started
-----------

For usage instructions, see the [homepage](http://papaparse.com) and, for more detail, the [documentation](http://papaparse.com/docs).



Tests
-----

Papa Parse is under test. Download this version from the [original repository](https://github.com/mholt/PapaParse/releases/tag/4.1.1), run `npm install`, then `npm test` to run the tests in your browser.



Contributing
------------

To discuss a new feature or ask a question, open an issue. To fix a bug, submit a pull request to be credited with the [contributors](https://github.com/mholt/PapaParse/graphs/contributors)! Remember, a pull request, *with test*, is best. You may also discuss on Twitter with [#PapaParse](https://twitter.com/search?q=%23PapaParse&src=typd&f=realtime) or directly to me, [@mholt6](https://twitter.com/mholt6).


---

# Disclaimer

This repository is a mirror of the [papaparse](https://www.npmjs.com/package/papaparse) package for Node JS. It mirrors all versions from 4.0.0 onwards since this is when the package was first published to NPM. The reason this is a completely separate repository and not a fork is to keep the repository as small as possible without any unnecessary files. The original work is licensed under MIT and as such, I claim no personal copyright over this publication. All credit should go to the original developers ([@mholt](https://github.com/mholt), [@pokoli](https://github.com/pokoli), et al.)

This is not an official project. I have never directly worked on the 'papaparse' library and I am in no way affiliated with [@mholt](https://github.com/mholt), [@pokoli](https://github.com/pokoli), or any of their respective contributors. This is only a mirror of a package across different versions which have been published to NPM. I will not be actively maintaining the code itself but I will publish mirrors of new versions as they are released.

\-[@tjohnston-softdev](https://github.com/tjohnston-softdev)

---

**Compiled:** 17 October 2021  
**Released:** 23 October 2021

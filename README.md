# What is different from original [adm-zip](https://www.npmjs.com/package/adm-zip)?
Added support zip entry filename encoding.
```javascript
/* Supports decompression only to avoid spreading more chaos! */
  var zip = new AdmZip("./file_made_by_windows.zip", "shiftjis");
```
Supported encodings are based on [iconv-lite](https://www.npmjs.com/package/iconv-lite).
The main target of this module is zip created on Windows.

# Installation

With [npm](http://npmjs.org) do:

    $ npm install adm-zip-with-enc
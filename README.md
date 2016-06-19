# filewalk

## Description
Recursively get all files in a given directory


## Usage
```
var filewalk = require('rs-filewalk');

var files = filewalk("~/Downloads");
```
Output:
```
files = [
  {
    file: "example.txt",
    folder: "~/Downloads",
    base: "~/Downloads"
  },
  {
    file: "example2.txt",
    folder: "~/Downloads/Test/Recursive/Folder",
    base: "~/Downloads"
  }
];
```

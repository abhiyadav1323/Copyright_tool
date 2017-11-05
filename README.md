## Copyright_tool

This script adds copyright to files having no copyright and updates the copyright in the file having an old copyright text.

## Installing / Getting started

* Clone the repository by typing the following command in the shell.
```shell
git clone https://github.com/abhiyadav1323/Copyright_tool.git
```

## Important Details
* The script works by first finding a particular pattern, if found, deletes the text between the pattern including the pattern. Then it adds the new copyright text at the beginning of a file within that particular pattern.
* File named "copyright.txt" will contain actual copyright text.
* File named "remove.txt" will contain full path of files to be excluded with each file name in new line. For example:- 
```shell
/home/abhishek/Desktop/a/1/task.rb
```
* Following extensions are added to copyright script:
```shell
  > .sh, .yml, .rb, .coffee, .properties
  > .c, .cpp, .h, .js, .java
  > .html, .php, .xml, .xsd, .erb
  > .css, .scss, .scssc
```

### How to use?
* All three files, viz. "copyright_tool", i.e. copyright script, "copyright.txt", "remove.txt", should be present in same directory.
* This copyright script will add copyright to all files within that directory and sub directories.
* Open the terminal. Go to the directory where the "copyright_tool", i.e. copyright script, is. And just run the command "./copyright_tool" or "bash copyright_tool". This will add the copyright to all the files except the files whose name is written in remove.txt.

## Licensing

The MIT License (MIT)

Copyright (c) 2016 Abhishek Yadav

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

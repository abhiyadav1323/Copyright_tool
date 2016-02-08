# Copyright_tool

### Important Details
1. This script adds copyright to files having no copyright and updates the copyright in the file having an old copyright text.
2. The script works by first finding a particular pattern, if found, deletes the text between the pattern including the pattern. Then it adds the new copyright text at the beginning of a file within that particular pattern.
3. File named "copyright.txt" will contain actual copyright text.
4. File named "remove.txt" will contain full path of files to be excluded with each file name in new line. For example:- /home/abhishek/Desktop/a/1/task.rb
5. Proper comments are added in the "copyright_tool" about the arguments taken by the funtion if someone needs to edit it.
6. Following extensions are added to copyright script:
  * .sh, .yml, .rb, .coffee, .properties
  * .c, .cpp, .h, .js, .java
  * .html, .php, .xml, .xsd, .erb
  * .css, .scss, .scssc

### How to use?
1. All three files, viz. "copyright_tool", i.e. copyright script, "copyright.txt", "remove.txt", should be present in same directory.
2. This copyright script will add copyright to all files within that directory and sub directories.
3. Open the terminal. Go to the directory where the "copyright_tool", i.e. copyright script, is. And just run the command "./copyright_tool" or "bash copyright_tool". This will add the copyright to all the files except the files whose name is written in remove.txt.


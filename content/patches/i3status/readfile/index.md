---
title: "Readfile"
date: 2019-01-28T10:13:56+01:00
description: "Readfile adds functionality to print file contents"



type: "page"

creatordisplayname: "Dennis Vesterlund"
creatoremail: "dennisvesterlund@gmail.com"
lastmodifierdisplayname: "Dennis Vesterlund"
lastmodifieremail: "dennisvesterlund@gmail.com"
---


# Readfile
Readfile is a patch that adds the functionality to print content of a file to the statusline.
It removes all the newlines before printing.


## Manpage
```
=== File Contents

Outputs the contents of the specified file. You can use this to check contents
of files on your system, for example /proc/uptime. By default the function only
reads the first 254 characters of the file, if you want to override this set 
the Max_characters option. It will never read beyond the first 4095 characters.
If the file is not found "no file" will be printed, if the file can't be read
"error read" will be printed.

*Example order*: read_file UPTIME

*Example format*: "%title: %content"

*Example path*: "/proc/uptime"

*Example Max_characters*: 255

```


## Downloads

### Patches
- [i3status-readfile-20190128-be0be59.diff](i3status-readfile-20190128-be0be59.diff)
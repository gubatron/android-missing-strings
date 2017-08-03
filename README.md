# AMS (android-missing-strings)

**ams** (android-missing-strings) is a simple command line reporting tool to know what strings need to be translated on an android project.

The output of ams is a text file friendly to a non-coding person who can be in charge of managing the translators involved in the project.

It can also be used to delete left over translation entries that have been deleted from your main string.xml

## Requirements
 - Python 2.6+


## Installation
Make sure you have the **ams** source folder on your $PATH environment variable.

## Usage:
from within any android project, just execute

```bash
ams - Android Missing Strings reporting tool.
    
    Usage:
    ams [-l xx[,yy,zz...]] [--cleanleftovers] -o <output_file>

    Options:
    -h --help            Print this help


    -l --lang <xx>       Specify a language or many with comma separated 2-char language codes.

                         e.g:  -l cn         (creates report for Chinese strings.xml)
                               -l cn,it,fr   (creates report for Chinese, Italian and French strings.xml files)

                         If this parameter is ommited, a report with every language file found will be created.


    -o --oFile           Specify the output file name for the report

    --cleanleftovers     Removes left over translations on other language files

    Copyright (c) 2014-2017 - The Mit License (MIT)

    Authors:
    Angel Leon <gubatron@gmail.com>
    Katay Santos <kataysantos@gmail.com>
```

## License
Copyright (c) 2014-2017 - The Mit License (MIT)

## Authors
 - [Angel Leon](https://github.com/gubatron/) 
 - [Katay Santos](https://github.com/cateye/)

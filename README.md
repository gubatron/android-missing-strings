# AMS (android-missing-strings)

**ams** (android-missing-strings) is a simple command line reporting tool to know what strings need to be translated on an android project.

The output of ams is a text file friendly to a non-coding person who can be in charge of managing the translators involved in the project.

## Requirements
 - Python 2.6+


## Installation
Make sure you have the **ams** source folder on your $PATH environment variable.

## Usage:
from within any android project, just execute

```bash
ams [-l xx[,yy,zz...]] -o <output_file>

    Options:
    -h --help            Print this help


    -l --lang <xx>       Specify a language or many with comma separated 2-char language codes.

                         e.g:  -l cn         (creates report for Chinese strings.xml)
                               -l cn,it,fr   (creates report for Chinese, Italian and French strings.xml files)

                         If this parameter is ommited, a report with every language file found will be created.


    -o --oFile           Specify the output file name for the text report
```

## License
Copyright (c) 2014 - The Mit License (MIT)

## Authors
 - [Angel Leon](https://github.com/gubatron/) 
 - [Katay Santos](https://github.com/cateye/)

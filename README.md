
rtf-filter reads a Rich Text Format (RTF) word processing file and outputs a plain text version with only line breaks and whitespace as formatting.

## Installation

Ensure boost development libraries are installed.  E.g. on Debian...

`apt-get install libboost-program-options-dev`
`apt-get install libboost-filesystem-dev`

And the C++ toolchain:

`apt-get install build-essential`

Then compile the code:

```
./configure 
make
make install
```

The program will be installed as rtffilter.

## Notes On MAC OSX



You might need to install boost, so using homebrew:

`brew install boost`

## Bug reports

If you discover a problem with rtf-filter, we would like to know about it.

## License

COMMON DEVELOPMENT AND DISTRIBUTION LICENSE (CDDL) Version 1.0
Copyright PS Computer Services Ltd 2003-2011

# an.vil
Anvil (stylized as "an.vil") is a set of various libraries written in [EVIL](https://github.com/vddCore/EVIL). The intention is to expand the base functionality of the default EVIL Runtime with features commonly used in programming.

**Note:** These libraries as well as the EVIL Language are still under active development. Breaking changes may occur at any time.



## What features does this have?

As of right now, Anvil features three libraries:

### strlib
Various String-related utility functions such as turning numbers into strings with configurable bases, substring-replacement and -counting and base64 encoding and decoding.

### arrlib
A library focused on utility functions around Arrays, heavily inspired by JavaScript. As of right now, `map`, `filter` and `reduce` functions are included, all with the same functionality as their JS counterparts.

### hashlib
Somewhat specific functionality related to hashing of data. Currently, only the calculation of CRC-8 Checksums is supported.



## How can I use this?

The easiest way of installing Anvil is by cloning this repository into the default `include` folder of your EVIL installation. Updating the libraries is as simple as pulling the newest version from the repository, and you can reference all libraries in the repository no matter where your project workspace is located.

All initialization is done using `vminit`-annotated functions, so no extra steps need to be taken. As soon as the library files you need are included, everything is ready to go!

**Note:** When including multiple library files, you may get a warning about certain vminit functions being redeclared. If you haven't defined any functions with those names yourself, this is not an issue.



## Where's the documentation?

As of right now, there is none. As this project matures, documentation will be written. For now, the codebase is small enough to be able to understand its features by just checking the code.
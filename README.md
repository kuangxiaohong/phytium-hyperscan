# Hyperscan

Hyperscan is a high-performance multiple regex matching library. It follows the
regular expression syntax of the commonly-used libpcre library, but is a
standalone library with its own C API.

Hyperscan uses hybrid automata techniques to allow simultaneous matching of
large numbers (up to tens of thousands) of regular expressions and for the
matching of regular expressions across streams of data.

Hyperscan is typically used in a DPI library stack.

# Documentation

Information on building the Hyperscan library and using its API is available in
the [Developer Reference Guide](http://intel.github.io/hyperscan/dev-reference/).

# License

Hyperscan is licensed under the BSD License. See the LICENSE file in the
project repository.

# Versioning


The `main` branch on Github will always contain the most recent 
release that supports the aarch64 architecture. The aarch64 branch was developed
based on Intel hyperscan 5.2.1. Each version released to main branch goes through
QA and testing before it is released; if you're a user of aarch64, rather than a developer,
this is the version you should be using.

# Porting
Perform platform-specific different operations, including compilation options, 
detection specific header files, SIMD instruction judgment, and so on.

# Optimization
Improve the phytium platform by using the NEON instructions, etc

# Get Involved

The official homepage for Hyperscan is at [www.hyperscan.io](https://www.hyperscan.io).


If you wish to contact the Hyperscan team at Intel directly, without posting
publicly to the mailing list, send an email to
[hyperscan@intel.com](mailto:hyperscan@intel.com).

`aarch64` branch

If you have questions or comments, we encourage you to create an issue on Github.


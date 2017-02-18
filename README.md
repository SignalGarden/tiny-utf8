# tiny-utf8
Lightweight C++11 library for embedding Unicode 
Originally found at: https://sourceforge.net/projects/tiny-utf8/ 
Original Author: ijake1111

This repository exists to capture the latest and most stable builds for our use.

Features
Drop-in replacement for std::string
Very Lightweight ~2k LOC
Very Fast
sizeof(utf8_string) = 24bytes (x86)
Codepoint Range: 0x0 - 0x7FFFFFFF (6 Bytes)
Single Header file, Single Source file
NO Exceptions (Defensive Programming)
Straightforward C++11 design
Even Understands ANSI Strings (Characters 127-255) (with the above mentioned limitations)
Prepend the UTF8 BOM (Byte Order Mark) to any string when converting it to an std::string
Supports raw (Byte-based) access (where Speed is needed)
WHAT TINY-UTF8 DOES NOT:
- conversion between iso encodings and utf8
- other unicode encodings like UTF16 or UTF32
- visible character comparison ('ch' vs. 'c'+'h')
- codepoint normalization

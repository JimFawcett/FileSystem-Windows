# FileSystem-Windows

https://JimFawcett.github.io/FileSystem.html

Library for managing directory content.  Provides a FileSystem namespace with interface modeled after the .Net System.IO namespace.
FileSystem provides File, FileInfo, Directory, and Path classes.  It uses the windows API for directory access.

I will replace the API calls with std::filesystem when that becomes part of the C++20 standard.

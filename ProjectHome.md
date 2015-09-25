# Zeta Enterprise Library #
A small set of general-purpose classes for using in .NET applications (2.0 or higher)

![http://i3.codeplex.com/Project/Download/FileDownload.aspx?ProjectName=zetaenterpriselib&DownloadId=75853&img=image.png](http://i3.codeplex.com/Project/Download/FileDownload.aspx?ProjectName=zetaenterpriselib&DownloadId=75853&img=image.png)

## Introduction ##
In my daily live as a programmer, I started centralizing some functions I use regularily into a central library. Probably every developer does this some time in his life.

This project presents you the resulting library.

That said, my library is nothing special or even rocket science. It is a rather minimalistic documented and commented set of function from the areas:

  * Web (ASP.NET)
  * Windows (Windows Forms)
  * Logging (wrapping LOG4NET)
  * Database access (wrappers for OleDB, SQL Server, Oracle)
  * Data compression (ZIP)
  * General purpose functions for e.g. string manipulation, XML manipulation, type conversions

You can use the library from any .NET application that uses the **.NET Framework 2.0** or higher.

I started developing some unit tests in the recent month but did not yet cover the whole library (if I ever will at all).

Originally I did not intend to provide the source or to provide an article at all about this library, but since nice people asked me to do so, here it is.

The library exists and is constantly enhanced since approximately 5 years. The latest application that uses it is or [Zeta Test](http://www.zeta-test.com) tool, an application for test case management. Therefore you can expect it to be rather stable and hopefully rather bug-free. But because of the fact that I never planned to release the library and that the library is mostly used by myself only (few exceptions), probably the design and documentation (through comments, only) isn't as good as it could be.

## Goals of this Article and the Library ##

Probably you don't find any usage for all of the functions of the library. But maybe the one or the other class is something you looked for in the past. If this is true for you, you could either use the whole library with the DLL files, or you could extract the source code and compile it with your own projects.

## Using the Code ##

To get working examples of how to use the library, for now please refer to the [Zeta Resource Editor](http://code.google.com/p/zetaresourceeditor/) project here on Google Code that makes heavy use of the Zeta Enterprise Library.

## Epilog ##

This article gave you a quick overview about a set of general purpose function for .NET 2.0. If you have any questions, comments or bug reports, please file them in the [Issues tab](http://code.google.com/p/zetaenterpriselib/issues/list) for this project.

Thank you!

## History ##

  * **2009-07-19** First release of the library to Google Code. The project also exists on [CodePlex](http://zetaenterpriselib.codeplex.com/).
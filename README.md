CoreGraphics Information Disclosure - CVE-2014-4378
===================================================

This article explores the exploitability of MobileSafari on IOS 7.1.x. Using a crafted PDF file as an HTML image makes it possible to leak information about the memory layout to the browser Javascript interpreter. Apple CoreGraphics library fails to validate input when parsing the colorspace specification of an inline image embedded in a PDF content stream. he issue results in an information leak vulnerability that improves the adversary capability of exploit other vulnerabilities in any application linked with this library. This is also proved useful to bypass a several exploit mitigations such as ASLR, DEP and CodeSigning.

Sumary:
=======
* Title: Apple CoreGraphics Information Disclosure
* CVE Name: CVE-2014-4378
* Permalink: http://blog.binamuse.com/2014/09/coregraphics-information-disclosure.html
* Date published: 2014-09-18
* Date of last update: 2014-09-18
* Class: Client side / Out of bounds memory read
* Advisory: HT6441 HT6443

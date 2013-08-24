Test Document Generator/Permutator for Apache OpenOffice
======

OpenOffice contains a word processor (Writer), a spreadsheet (Calc), a presentation application (Impress), a drawing application (Draw), a formula editor (Math), and a database management application (Base).
OpenOffice's default file format is the OpenDocument Format (ODF), an ISO/IEC standard, which originated with OpenOffice.org. It can also read a wide variety of other file formats, with particular attention to those from Microsoft Office.
Apache OpenOffice is developed for Linux, OS X and Windows, with ports to other operating systems. It is distributed under the Apache License.
A continuing challenge in testing software is an efficient way to generate test cases, in particularly in case of Apache Open Office, generating test cases like various text styles, border styles, alignment etc... A complete test would require creation of large number of test case manually.
This project indents to generate all possible test cases or documents using open source libraries in java like Apache ODF Toolkit and Apache POI.
Here the goal is to produce a software that is able to permutated all possible combinations of test cases with minimum head ache to the tester, but he should be able to design the test case generated. The software is indented to produce a subset of X*Y*Z sets of test case.
# docx2html
docx2html is a native java library that provides an API for breaking a single docx-file (or a folder that contains multiple docx-files), taken from the local file system, into distinct html-section-files. The aim of this process is the automatic segmentation and extraction of parts of docx-files, based on format characteristics. The library operates in two phases. The first one converts each docx-file into a single html-file, and the second breaks each html-file into a set of html-section-files, based on the particular segmentation (splitting) rules that are defined in the configuration (explained below).
The conversion into html is dependend on `fr/opensagres/xdocreport/fr.opensagres.poi.xwpf.converter.xhtml`

The source code of the library is hosted at gitlab:  **https://gitlab.com/axaridou/docx2html.git**


Publishing EPUB3
================

## Zip distribution


    EPUB3 files are actually just plain zip files. So the first thing to know 
is how to make a zip file:

```bash
 $ cd
 $ mkdir book
 $ cd book

 $ # create all content!

 $ zip book .* *
 $ ls
```

    At this point, you should see a zip file which includes all the content in 
the folder you called 'book.' If your file is meant to be an EPUB, you can:

```bash
 $ mv book.zip book.epub
```

## Required files

    To validate an EPUB3, it must have these two folders, META-INF and OEBPS, 
and a *mimetype* file. Content happens in the OEBPS folder, which should have: 

* bookcover.xhtml
* toc.xhtml
* title.xhtml
* copyright.xhtml
* chap01.xhtml
* chap02.xhtml
* chap03.xhtml
* backcover.xhtml










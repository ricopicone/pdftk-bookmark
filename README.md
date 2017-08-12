# pdftk-bookmark

This is a simple Python script for adding bookmarks to a pdf with [PDFtk Server](https://www.pdflabs.com/tools/pdftk-server/). It was developed on macos, but should work under any *nix system with Python and PDFtk Server installed.

## Quick start

Clone and add the directory to your path.
Now navigate to the directory of the pdf to which you would like to add a bookmark and execute the following command.

```console
$ pdftk-bookmark <pdf file> <bookmark page number> <bookmark title>
```

## Notes

Be sure to quote bookmark titles with spaces. For now, you must bookmark in sequential order (earlier bookmarks first). Hopefully, a future version will allow proper re-ordering by page number. Finally, there is no bookmark delete functionality, yet.

## To do

1. Delete bookmark functionality.
2. Re-order bookmarks by page number.
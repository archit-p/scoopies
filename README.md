# Scoopies v1.0.2

A text-editor similar to Kilo by antirez (https://github.com/antirez/kilo), created in C.

This version doesn't come with syntax-highlighting and search, however expect that to be added in future versions.

The entire text-editor is written in only ~700 lines of code in a single C file.

Changes and differences from Kilo:

1. Not allowing the cursor to go below the last line of text. This was earlier causing a seg-fault.
2. The way we exit from the editor has been changed. When the user wants to exit without making changes to the file, a prompt is displayed.

The tutorial used to make this editor can be found here:
    https://viewsourcecode.org/snaptoken/kilo/

This is a wonderful tutorial, and teaches how to make a CLI without the use of any libraries (not even curses).

The project made use of the Coala code linter for fixing the look of the code. The linter can be found here at: https://github.com/coala/coala

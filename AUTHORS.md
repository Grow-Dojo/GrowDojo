#Recording Contributors
Keep correct records of which portions were written by whom. This is very important. These records should say which files or parts of files were written by each person, and which files or parts of files were revised by each person. This should include installation scripts as well as manuals and documentation files—everything.

These records don’t need to be as detailed as a change log. They don’t need to distinguish work done at different times, only different people. They don’t need describe changes in more detail than which files or parts of a file were changed. And they don’t need to say anything about the function or purpose of a file or change—the Register of Copyrights doesn’t care what the text does, just who wrote or contributed to which parts.

The list should also mention if certain files distributed in the same package are really a separate program.

Only the contributions that are legally significant for copyright purposes (see Legally Significant) need to be listed. Small contributions, bug reports, ideas, etc., can be omitted.

For example, this would describe an early version of GAS:
```
Dean Elsner   first version of all files except gdb-lines.c and m68k.c.
Jay Fenlason  entire files gdb-lines.c and m68k.c, most of app.c,
              plus extensive changes in messages.c, input-file.c, write.c
              and revisions elsewhere.

Note: GAS is distributed with the files obstack.c and obstack.h, but
they are considered a separate package, not part of GAS proper.
```
AUTHORS in the source directory for the program itself.

You can use the change log as the basis for these records, if you wish. Just make sure to record the correct author for each change (the person who wrote the change, not the person who installed it), and add ‘(tiny change)’ for those changes that are too trivial to matter for copyright purposes. Later on you can update the AUTHORS file from the change log. This can even be done automatically, if you are careful about the formatting of the change log entries.

It is ok to include other email addresses, names, and program information in AUTHORS, such as bug-reporting information.

original source 🌐
https://www.gnu.org/prep/maintain/html_node/Recording-Contributors.html

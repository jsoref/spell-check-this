# Supplemental dictionary files (Allow)

## Syntax

One word per line (only letters and `'`s allowed).

## Files

Each file with the extension `.txt` will be treated as additional content for the dictionary.

* [allow.txt](allow.txt) - is a basic file for additional words
* [dictionary-workflow.txt](dictionary-workflow.txt) - covers words used by [dictionary.yml](../../../workflows/dictionary.yml) - if you delete that file, you can delete this file.

## Notes

You can have as many distinct files as you like.

You could have a file just for people's names,
or a file for HTML markup tags,
or a file for CSS markup tags,
or a file for Java reserved words,
...

If you choose to use some fancy organization for these files, you should probably update this file to help others maintain them.

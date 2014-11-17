Open Metrical Psalter
=====================

This is the Open Metrical Psalter, a project of the Open Liturgy Project.

The purpose of the Open Metrical Psalter is to provide easy access to a large collection of Public Domain and Open-license metrical paraphrases of Psalms, and also hymns based on Psalms.


## Types of Hymn Texts
All contributed texts should be:
 - A direct metrical paraphrase of a Psalm /OR/ obviously inspired by a specific Psalm text. And clearly labeled as such.
 - In the Public Domain /OR/ released into the commons using a Free Culture license which allows both adaptation and commercial use.
 - Strictly in a recognizable hymn meter (not irregular).

## Repo structure
 - Each Psalm (according Masoretic/Hebrew/Protestant numbering) has a directory. Directories are numbered with three digits and leading zeroes. 
 - Within each Psalm directory, metrical paraphrases are saved as .md files within that directory (not a sub-folder), with the title (usually the first line) in all-lower-case-letters-with-hyphens-for-spaces.
 - Hymns which are not (strictly speaking) metrical paraphrases, but are rather inspired by the Psalm should be placed within a subfolder labeled "/inspired-by/".


 ## Text file format
 - All files should have the extension .md (markdown), and contain no styling or formatting information.
 - A file header should be included to specify text information such as author, meter, license, portion of psalm (ie, which verses) set, etc. The header should end with three dashes on a single line. 
 - Text should be syllabified, using a double hyphen (this makes it easier to process with Lilypond and other automated score generators).

``` 
title: The King of Love my Shepherd Is 
author: Henry Williams Baker 
verses: 1-6 (all) 
license: Public Domain 
meter: 8.7.8.7. 
--- 
The King of Love my shep -- herd is 
Whose good -- ness fails me nev -- er.
```

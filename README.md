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
 - Each Psalm (according Masoretic/Hebrew/Protestant numbering) has a directory. Directories are numbered with three digits and leading zeroes. (This will ensure that the directories appear in their proper order.)
 - Within each Psalm directory, metrical paraphrases are saved as .md files within that directory (not a sub-folder), with the title (usually the first line) in all-lower-case-letters-with-hyphens-for-spaces.
 - Hymns which are not (strictly speaking) metrical paraphrases, but are rather inspired by the Psalm should be placed within a subfolder labeled "/inspired-by/".


## Text file format
 - All files should have the extension .md (markdown), and contain no styling or formatting information.
 - A file header should be included to specify text information such as author, meter, license, portion of psalm (ie, which verses) set, etc. The header should begin and end with three dashes on a single line. 
 - Text should be syllabified, using a double hyphen and spaces (this makes it easier to process with Lilypond and other automated score generators).
 - In order to insert a working line break at the end of a line of text (as in the lines of a stanza), type two spaces after the last character of the line, before hitting [Enter].

## Discussion of Texts
 - If you are working on a new text and would like to discuss it, open an Issue.
 
## Corrections of Texts
 - If a text is the work of a living person who contributed the text to the repo, please do not take it upon yourself to "fix it," except for in the case of simple and obvious typos, misspellings, etc. (If you notice typos, don't open an issue - just edit it and create a pull request.)
 - If you have a great idea to alter someone else's text, you can open an issue to discuss your proposed change (which, normally, should be agreed upon by the authoer before the original file is altered). OR
 - You may use the original text as the basis for a NEW text, which you are free to submit to the repo. (The Creative Commons License ALLOWS you do to this, but not everything that is legal is good: please consider the value in adding an altered version of an existing text and do not abuse the system.)

## Public Domain Texts
 - In most cases, the desire is for the most well-attested version of a text, with as much completeness as possible.
 - If you only have access to an abridged or altered text, go ahead and submit it. Create an issue mentioning that you know more is available somewhere but you can't find it.
 - If you see a text that you know has an older r more complete version, edit the file and submit a pull request.
 
## Altering Texts Because of Reasons (for example, gender inclusivity or theological content)
 - This project should be EXPANSIVE, not restrictive. If you have a need for an altered version of a text FOR ANY REASON, it is possible others do too. (There are limits to this, of course.)
 - Leave the original in the repo, do not try to alter the original *in situ*.
 - Create a new file, with a copy of the original. Commit THIS VERSION in your fork.
 - Make your edits. Commit this version and issue a pull request.
 - By making a commit after you've copied the text into a new file, but BEFORE you alter the text, there will be a record of what changes you made. This commit history will be included when your fork gets merged back into the main repo. This kind of "edit trail" is very helpful.

``` 
---
title: The King of Love my Shepherd Is 
author: Henry Williams Baker 
verses: 1-6 (all) 
license: Public Domain 
meter: 8.7.8.7. 
--- 
The King of Love my shep -- herd is 
Whose good -- ness fails me nev -- er.
```

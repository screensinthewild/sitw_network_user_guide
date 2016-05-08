sitw_network_user_guide

Authors:  Lei Ye, Steve North & Holger Schnädelbach
Author URI:  http://www.cs.nott.ac.uk/~pszsn/
License: AGPLv3 or later
License URI: http://www.gnu.org/licenses/agpl-3.0.en.html
Can: Commercial Use, Modify, Distribute, Place Warranty
Can't: Sublicence, Hold Liable
Must: Include Copyright, Include License, State Changes, Disclose Source
This research was originally funded in the UK under EPSRC grant reference EP/I031839/1 and title ‘Exploring the potential of networked urban screens for communities and culture’.

Copyright (c) 2015, The University of Nottingham

This is the user guide for the 'Screens in the Wild' framework for buidling an urban screens network.

This code was developed between 2011 and 2015.

The code and various modules required to implement this are in the Github repository: 'sitw_core'.

We have included the Word Document and a copy of it converted to Markdown format.

Using the CLI tool Pandoc (under Windows), we can convert Word to Markdown.

This allows Github to do DIFF comparisons on the Markdown version, showing how the text has changed between versions.

Under Windows, install Pandoc. Add the install path for Pandoc to the Windows system %path% variable.
Under Windows 7, this was: C:\Users\<username>\AppData\Local\Pandoc

Open Command Prompt in the folder containing the documents.

Convert Word 2 Markdown:
pandoc -f docx -t markdown -o sitw_network_user_guide.md sitw_network_user_guide.docx

Note: conversion backward to Word seems to lose any embedded images and doesn't accurately recreate the formatting.

See:
https://gist.github.com/aembleton/1eb889bc443996a508df
https://github.com/jgm/pandoc/releases/tag/1.17.0.2
# Bruhman Translator's Bible (BTB)


A powerful and comprehensive digital Bible compiled in markdown for the [Obsidian](https://obsidian.md) platform.
## Overview

Typically used as a personal note-taking solution, in this application the fast and powerful Wikipedia-style linking features of [Obsidian](https://obsidian.md) lend themselves mightily to the many still-relevant and freely available Bible resources found in the public domain.

Endless thanks to all of the proud scholars, theologians, and scribes who did the real work that made a project like this possible.  This Bible was built on the backs of many who began their painstaking work digitizing, analyzing, and correcting centuries-old publications, years before modern tools made such tasks easier.  Also, special thanks to the groups and individuals listed [below](#Acknowledgments), who made their work freely available to the public and provided the source data for this project.

*The first iteration is somewhat complete, but it only scratches the surface of what could be done leveraging the Obsidian platform.  Endless possibilities include: full text search in bases, topical concordances which can be applied to verses as properties or tags, a team-style workflow for managing translation projects, additional bible versions, 'Scripture Quoting Scripture' cross-references, etc.*

**Important:** Initial setup takes a little while, but once the indexing is complete everything runs lightning fast. After cloning the repository, or downloading and unzipping the archive of over 100,000 individual "notes" that make up the Bible, the first index can take about an hour, more or less.
## Screenshots
#### CHAPTERS
![Chapter View](/lexicon/views/ChapterView.png)
#### RED-LETTERS & CROSS-REFERENCES
![Chapter View](/lexicon/views/RedLetters.PNG)
#### VERSES
![Verse View](/lexicon/views/VerseView.PNG)
#### LEXICON
![Chapter View](/lexicon/views/Lexicon.PNG)
#### MAPS
![Chapter View](/lexicon/views/Maps.PNG)

## Features
- Full chapters feature the **KJV** text with **Jesus' words in red-letters**.
- Chapters are divided by section headings from the **Berean Standard Bible** (with cross-references) for easy reading.
- Full chapters also include all 500,000+ references and notes from the expansive **Treasury of Scripture Knowledge** which are available as Obsidian footnotes aligned with their catchwords (and which appear to be the primary source of the extensive ESV references and notes).
- Individual verses (easily accessible from chapter view) include the verse text from the **KJV** representing the majority text.  
- All **Septuagint** interlinear text is available directly from the Masoretic text and vice versa.  This allows you to easily see the same scripture used during the 1st century which is often quoted in the New Testament.
- Text from the **Berean Standard Bible** is also included in the verse view for quick reference to a modern translation of the critical text.
- Individual verses are broken down in an interlinear format, displaying the unicode word in the original language (color-coded: **red** for **Hebrew**, **green** for **Aramaic**, **purple** for **Greek** - and **orange** for **Latin** in a few places), a link to the lexical entry for every Strong's tagged word, and a hover preview of full explanations for parts-of-speech & morphology.
- Also included in the verse view are translator's notes from the **Translator's Amalgamated Hebrew Old Testament and Greek New Testament**, explaining word order differences between sources, the different spellings or definitions, and which sources include or exclude which words, phrases, and verses.  It's like having a reference to every source text all in one easy interface.
- The lexicon contains pages compiled for every unambiguated Strong's number from all available entries found in:
   - **Strong's** Exhaustive Concordance
   - **Brown-Driver-Briggs** Hebrew English Lexicon of the Old Testament
   - **Abbott Smith** Greek Lexicon of the New Testament
   - **Liddell and Scott's (LSJ)** Greek-English Lexicon
   - **Robinson's Morphological Analysis Codes**
   - **Translator's Brief Lexicon of Extended Strong's for Greek & Hebrew**
   - **Translator's Individualized Proper Names**, which includes articles on individual people and detailed entries about place names including Google Maps for places with geocoding (requires a Google API key.)

## Installation
1. Download or clone this repository
2. Open the folder as a vault in [Obsidian](https://obsidian.md)
3. **Be patient during initial indexing** - Obsidian will need time (potentially up to an hour)
4. Enable CSS snippets and select the btb.css snippet file which is installed in the .obsidian folder and found in the root of this repository.
5. Change your settings so that reading view is the default when opening notes.
6. If you would like to use the maps features you have to sign up for a [Google developer API key](https://developers.google.com/maps/documentation/javascript), and then use VS Code to do a global find and replace of '\[GoogleAPIKey\]' with your key.

There are no ***required*** Obsidian plugins, but there are a multitude of them that could be useful.
### Source Material Licenses
The underlying Bible texts and reference materials used in this project are in the public domain or used under their respective open licenses. See the Acknowledgments section below for details on individual resources.
## Acknowledgments
Thank you to Dr. Charles Vanderpool, who very generously gave permission to use his [Apostolic Bible Polyglot](https://apostolicbible.com/), from which the Septuagint text and interlinear data were derived.  If you are interested in New Testament and Septuagint Greek, [his website](https://apostolicbible.com/) offers free downloadable resources.  Please [make a purchase at his bookstore](https://www.apostolicbible.com/bookstore.htm) to support his amazing work.

This project would not have been possible without the generous contributions by [Tyndale House, Cambridge](https://tyndalehouse.com/) and the [Tyndale House Scholars](https://tyndalehouse.com/international-scholars-programme/) who did the motherload of work compiling all of the data and resources curated and made available by [STEPBible.org](https://STEPBible.org).  The full data repository can be found [here](https://github.com/STEPBible/STEPBible-Data).  Please visit the [STEP Bible website](https://www.stepbible.org/).  It's an outstanding, comprehensive resource of Bibles and supporting commentary and the inspiration for this Bible.

And a special thanks to the [CrossWire Bible Society](https://www.crosswire.org) who manage [The Sword Project](https://www.crosswire.org/sword/index.jsp) and host a multitude of freely-available Bibles, commentaries, and books found [here](https://www.crosswire.org/sword/modules/index.jsp) from which the red-lettering, and *The Treasury of Scripture Knowledge* cross-references are derived.

Strong's Concordance was compiled from the same source data as OpenScripture's Hebrew lexicon found [here](https://github.com/openscriptures/strongs) 

The [unabridged Brown-Driver-Briggs lexicon](https://github.com/eliranwong/unabridged-BDB-Hebrew-lexicon) for [Marvel.bible](https://marvel.bible/) with Strong's tagging and the Greek morphological codes from the [Open Greek New Testament](https://github.com/eliranwong/OpenGNT/) project are published by [Eliran Wong](https://github.com/eliranwong) who has contributed so much of his hard work to the public.

Most of the header info/comments found within the STEPBible Data repository are converted to markdown for reference, and also to aid with previewing morphology, abbreviations, explanations, etc. and those can be found here:

   - [Translator's Amalgamated Greek New Testament - TAGNT](lexicon/TAGNT.md)
   - [Translator's Amalgamated Hebrew Old Testament - TAHOT](lexicon/TAHOT.md)
   - [Translator's Brief lexicon of Extended Strong's for Greek - TBESG](lexicon/TBESG.md)
   - [Translators Expansion of Hebrew Morphology Codes - TEHMC](lexicon/TEHMC.md)
   - [Translators Expansion of Greek Morphology Codes - TEGMC](lexicon/TEGMC.md)
   - [Translators Formatted full LSJ Bible lexicon up to G5624](lexicon/TFLSJ_0-5624)
   - [Translators Formatted full LSJ Bible lexicon extra](lexicon/TFLSJ_extra.md)



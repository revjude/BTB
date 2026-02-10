## Bruhman Translator's Bible (BTB)

A Bible compiled in Markdown for the [Obsidian](https://obsidian.md) platform. This Bible provides English-speaking users access to study the scriptures in their original Greek and Hebrew.
### Overview

Every verse is broken down by the Greek or Hebrew in an interlinear format. Every word links to its comprehensive lexical entry to help you study, analyze, and understand the meaning of each original language word.  Use this Bible to develop your own translations of the original scripture by tapping into Obsidian's note-taking interface to note, track, and manage your studies.

This Bible can be studied individually or in a group setting.

This work builds on the efforts of many scholars, theologians, and scribes whose painstaking digitization, analysis, and correction of ancient publications began years before modern tools made such tasks easier. The groups and individuals listed in the [Acknowledgments](#acknowledgments) section below generously made their work freely available and provided the foundation for this project.

**Important:** Initial setup requires patience. After cloning the repository or downloading the archive of almost 150,000 individual "notes", it takes Obsidian up to an hour to build a database and index all the connections. Once complete, navigation is quick.  In spite of the wait, it's still faster than same-day Prime, and it's free.

#### Interlinear Verses with Translation Notes

![Verse View](/lexicon/views/TranslatorsNotes.PNG)

#### Study By Translating the Original Scripture

![Chapter View](/lexicon/views/Pericopes.PNG)

#### Easily Manage Translations and Notes via Obsidian Bases

![Chapter View](/lexicon/views/Bases.PNG)

#### Comprehensive Hebrew/Aramaic & Greek Lexicons

![Chapter View](/lexicon/views/Lexicon.PNG)

#### Maps

![Chapter View](/lexicon/views/Maps.PNG)

#### Scripture Quoting Scripture

![Chapter View](/lexicon/views/SQS.PNG)

#### Topical Concordance
Search over 20,000 topics and sub-topics
![Chapter View](/lexicon/views/Concordance1.PNG)
More than 100,000 cross-references
![Chapter View](/lexicon/views/Concordance2.PNG)

#### Chapters with Extensive Footnotes

![Chapter View](/lexicon/views/ChapterView.png)

#### Red Letters and Cross-References

![Chapter View](/lexicon/views/RedLetters.PNG)

## Features

- **Chapter View**: Full chapters from the majority text with Jesus' words in red letters, pericope headings with cross-references, and over 500,000 footnotes
- **Section Headings**: link to their pericope (sounds like calliope, not like periscope), Greek for "a cutting out", which is a page for every section where you develop your own translations and keep notes.
- **Multiple Translations**: Individual verses include a traditional translation from the majority text, a modern translation from the critical text, and a literal word-for-word translation from the original Greek, Hebrew, or Aramaic
- **Septuagint Integration**: Interlinear NT Greek and OT Hebrew verses, plus all OT Greek verses from the Septuagint with word-for-word translations. The Septuagint (LXX) was the Bible known to the NT author's and so represents the scripture often quoted or referenced in the NT.  This edition of the LXX is derived from the [Apostolic Bible Polyglot](https://en.wikipedia.org/wiki/Apostolic_Bible_Polyglot) and cross-referenced with the Masoretic text
- **Lexicon Links**: Each word links to its BTB lexicon entry, compiled from multiple sources and disambiguated (e.g., clicking "Mary" shows the entry for that specific person, not just the general name)
- **Scripture Cross-References**: Embedded references show where verses quote, reference, or allude to other passages—helpful when studying New Testament citations of the Septuagint
- **Translator's Notes**: Notes from the Translator's Amalgamated Hebrew Old Testament and Greek New Testament explain word order differences, variant spellings and definitions, and textual variations across sources
- **Nave's Topical Concordance**: Press the hotkey to search the concordance of more than 20,000 topics and sub-stopics with links to over 100,000 passages

## Installation

1. Download or clone this repository
2. Open the folder as a vault in [Obsidian](https://obsidian.md)
3. **Be patient during initial indexing** - Obsidian will need approximately one hour to index all files
4. Enable CSS snippets and select the `btb.css` snippet file (located in the `.obsidian` folder and the repository root)
5. Set reading view as the default when opening notes (in Obsidian settings)
6. (Optional) For map features, obtain a [Google Maps API key](https://developers.google.com/maps/documentation/javascript), then use VS Code to find and replace `[GoogleAPIKey]` with your key throughout the project

_Note: No Obsidian plugins are required, though [there are many](https://obsidian.md/plugins) that might further enhance usability._

## Source Material Licenses

The underlying Bible texts and reference materials used in this project are in the public domain or used under their respective open licenses. See the Acknowledgments section below for details on individual resources.

## Acknowledgments

This project relies entirely on the work of others who have made their scholarship freely available.

**Dr. Charles Vanderpool** generously granted permission to use his [Apostolic Bible Polyglot](https://apostolicbible.com/), from which the Septuagint text and interlinear data were derived. His [website](https://apostolicbible.com/) offers free downloadable resources for those interested in New Testament and Septuagint Greek. Consider [supporting his work](https://www.apostolicbible.com/bookstore.htm) through his bookstore.

[Tyndale House, Cambridge](https://tyndalehouse.com/) and the [Tyndale House Scholars](https://tyndalehouse.com/international-scholars-programme/) compiled the extensive data and resources made available by [STEPBible.org](https://STEPBible.org). Their full data repository is [here](https://github.com/STEPBible/STEPBible-Data). The [STEP Bible website](https://www.stepbible.org/) is an excellent resource and served as inspiration for this project.

The [CrossWire Bible Society](https://www.crosswire.org) manages [The SWORD Project](https://www.crosswire.org/sword/index.jsp) and hosts numerous freely-available Bibles, commentaries, and books [here](https://www.crosswire.org/sword/modules/index.jsp). The red-lettering and _The Treasury of Scripture Knowledge_ cross-references come from their resources.

The [Brown-Driver-Briggs lexicon](https://github.com/eliranwong/unabridged-BDB-Hebrew-lexicon) for [Marvel.bible](https://marvel.bible/) with lemma tagging and the Greek morphological codes from the [Open Greek New Testament](https://github.com/eliranwong/OpenGNT/) project are published by [Eliran Wong](https://github.com/eliranwong), whose contributions to the public have been invaluable.

### Reference Materials

Several reference materials from the STEPBible Data repository have been converted to markdown for reference:

   - [Translator's Amalgamated Greek New Testament - TAGNT](lexicon/TAGNT.md)
   - [Translators Expansion of Greek Morphology Codes - TEGMC](lexicon/TEGMC.md)
   - [Translator's Amalgamated Hebrew Old Testament - TAHOT](lexicon/TAHOT.md)
   - [Translators Expansion of Hebrew Morphology Codes - TEHMC](lexicon/TEHMC.md)
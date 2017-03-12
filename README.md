# What is Jieba-Morph?

Jieba-Morph is a version of MorphMan which (in addition to the usual Japanese and Space Delimited morphemisers) comes with an included Chinese morphemiser (Jieba), allowing it to perform similar operations on your Chinese flashcards as MorphMan currently does with Japanese and/or space delimited languages.

# What is MorphMan?
MorphMan is an Anki plugin that reorders language cards based on the words you known. This
__greatly__ optimizes your learning queue as you only get sentences with exactly one unknown word (see
[I+1 principle](https://github.com/kaegi/MorphMan/wiki/I-plus-1) for a more detailed explanation).

# Why isn't this just included with MorphMan proper? Why should we need to use a whole different version just to include Chinese?

This is not ready for inclusion in the main MorphMan branch due to issues packaging such a large dependency (Jieba) with all copies of MorphMan. It is here for those who need it, and I will try and keep the repository somewhat in step with the main MorphMan repo until this repository transitions to a module which can be downloaded and used with MorphMan, but not included in it as one whole package. This would be similar to the way MorphMan currently relies on MeCab support coming from the separate Japanese-Support plugin, rather than its own package of MeCab.

# Installation

To install Jieba-Morph download the latest .zip archive from the [here](https://github.com/NinKenDo64/Jieba-Morph/releases)
and extract all files to your _Documents/Anki/addons_. Your folder structure should look like this:

-   _Documents/Anki/addons/morphman.py_
-   _Documents/Anki/addons/morph/\*allFilesAndDirectories\*_

After restarting Anki you should see an entry called _morphman_ under _Tools -> Add-ons_. You can find information and troubleshooting tips [here](https://github.com/kaegi/MorphMan/wiki/Installation).

This plugin works for following languages:
-   languages with spaces: __English__, __Russian__, __Spanish__, __etc.__
-   __Japanese__: you additionally have to to install the _[Japanese Support](https://ankiweb.net/shared/info/3918629684)_ Anki plugin
-   __Chinese__: Chinese support is included in this version of MorphMan, but unavailable in kaegi's version
-   more languages can be added on request if morpheme-splitting-tools are available for it


# MorphMan Wiki

See the [MorphMan wiki](https://github.com/kaegi/MorphMan/wiki) for more information.

## All credit to kaegi for ressurecting and vastly improving the MorphMan project to make this possible. And for offering his assistance in troubleshooting Jieba-Morph's rocky start.

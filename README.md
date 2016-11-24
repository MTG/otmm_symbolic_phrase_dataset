[![DOI](https://zenodo.org/badge/45952799.svg)](https://zenodo.org/badge/latestdoi/45952799) [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-ff69b4.svg)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

# otmm_symbolic_phrase_dataset
__Data sets containing pieces in [SymbTr2](https://github.com/MTG/SymbTr) format segmented into phrases__

This study presents a large machine-readable dataset of Turkish makam music scores segmented into phrases by experts of this music. The segmentation facilitates computational research on melodic similarity between phrases, and relation between melodic phrasing and meter, rarely studied topics due to unavailability of data resources. It consists of 31362 phrases on a set of 480 scores of different compositions annotated by 3 experts. 

Please refer to the following publication if you use this data in your research:

> M. K. Karaosmanoglu, B. Bozkurt, A. Holzapfel, N. D. Disiacik, A symbolic dataset of Turkish makam music phrases, Folk Music Analysis Workshop (FMA), Istanbul, 2014.

The refactored code for automatic phrase segmentation can be found [here](https://github.com/MTG/makam-symbolic-phrase-segmentation).

The latest release has some minor changes from the original training score dataset such as UTF-8 encoding and duplicate file removal. For the deliverables of the paper including the original training dataset please visit:
http://www.rhythmos.org/shareddata/turkishphrases.html

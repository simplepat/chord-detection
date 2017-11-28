Dataset downloads
===================

The dataset used in this project is rather large. It is composed of the following files:

> **Training data downloads**
> 
> - Index: http://ddmal.music.mcgill.ca/datasets/billboard/billboard-2.0-index.csv. As each song is identified by an integer, this file mainly serves as an index, pointing to the song's name and artist
> - Audio features: http://ddmal.music.mcgill.ca/datasets/billboard/billboard-2.0-chordino.tar.gz. Each folder is the song's index, and it contains both two *.csv files containing all the chroma features for each of the song's time segment.
> - Annotations/labels: http://ddmal.music.mcgill.ca/datasets/billboard/billboard-2.0.1-lab.tar.gz . Same organization as the features here, a folder with the song's index contains *.lab files (time segment + chord)

The original download page: http://ddmal.music.mcgill.ca/research/billboard
#### 
> **Extra testing data downloads**
> 
> - The links to the chords annotations in *.lab format for this dataset is the following: http://www.isophonics.net/content/reference-annotations
> - The extraction of the audio features has to be done manually using the album references provided here: http://www.isophonics.net/content/reference-annotations . 
> - The features are extracted using the open-source NNLS Chroma plugin (https://code.soundsoftware.ac.uk/attachments/download/1691/nnls-chroma-1.1.tar.gz), plugged to the Sonic Visualizer software (http://www.sonicvisualiser.org/download.html), using MIREX reference parameters (http://www.isophonics.net/nnls-chroma)

#### 
A sample of this extraction can be found in the csv file joined with the submission.

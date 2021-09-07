## Text to IPA Expert System
This is a knowledge base and expert system in CLIPS that transcribes English text to its Standard American English phonetic transcription in IPA. The knowledge base consists of features for all possible phonemes in SAE as well as all letters of the alphabet. The system applies rules based on these features and their environments. There are orthographical rules to obtain a transcription and phonological rules to make the transcription more representative of natural speech.

## Installation
This project is compatible with CLIPS version 6.4.  

In the CLIPS IDE, load constructs from TextToIPA.CLP. To run, use (reset) and (run) commands in the IDE. The program only accepts alphabetic characters as the input text. Enter any non-alphabetic character to stop running. 

## Validation
To check for accuracy of individual words, most dictionaries give transcriptions. Cambridge dictionary’s transcriptions are consistent with IPA. 
https://dictionary.cambridge.org/

Some differences that can be accounted for are IPA characters that this program gives can also be written with diacritics that the dictionary may give, but the symbols look similar and are often without needing much knowledge of IPA.

Additionally, the dictionary may give the more general allophone even though the one used in natural speech is different (i.e., the ‘d’ sound in ‘ladder’ is represented by /d/ in the dictionary representation, but is actually pronounced as the flap /ɾ/ in natural speech. Both are allophones of the phoneme [d] and both representations are usually considered correct, though the goal here is to sound more natural. Similarly, a string of words may be pronounced differently than the words individually.

To check the accuracy of words or a string of text, the phoneme synthesis program can give a general idea of how it should sound. 
https://itinerarium.github.io/phoneme-synthesis/

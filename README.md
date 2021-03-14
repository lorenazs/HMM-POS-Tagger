#Basic Hidden Markov Model for POS Tagging
 
 This repo contains the final submission for the 1st project, in the Natural Language Processing Nanodegree Program (udacity).
 The main steps and activities implemented are:
 
 **Step1 - Read and pre process the data**  
  
 * Read the dataset from XXX
 And exploring it through the Dataset class (provided by udacity), giving easy access to partitions of the data for testing and training.  Some activities in this step:  
 * counting unique words in the dataset vocabulary
 * accessing words and tag sequences, for a given sentence obtain its corresponding tags
 * acceding pairs (word-tags)

**Step2: build a Most Frequent Class (MFC) Tagger** 
 As a baseline I developed a MFC Tagger, basically choosing the most frequent tag assigned to each word.  After the model was implemented, then some predictions were made and its accuracy was evaluated.

**Step3: Build an Hidden Markov Model (HMM) Tagger**  
Some activities o sub-steps implemented:  
* counting unigrams
* counting bigrams
* counting sequence starting
* counting sequence ending
* the implementation of the HMM Tagger
* decoding sequences with the implemented HMM Tagger

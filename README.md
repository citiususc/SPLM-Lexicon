# SPLM-Lexicon

SPLM is a ranked opinion lexicon. We obtained the weights assigned to each word-tag pair by making use of the equations defined on the following paper which describe all details about this lexicon.

# Format

The file is tab delimited with: 


 * Word: the words.


 * Tag: Part of speech (POS),

                 - r (adverb)
                 
                 - a (adjective).

 * Polarity: positive / negative.


* D(w): the final weight of the word according to the equations described in the following paper:
  If the value of D(w) is negative, w will be in the class of negative words.  If the value of D(w) is positive, w will be in a positive class. 

# Reference


Almatarneh, Sattam, and Pablo Gamallo. "Automatic construction of domain-specific sentiment lexicons for polarity classification." International Conference on Practical Applications of Agents and Multi-Agent Systems. Springer, Cham, 2017.


If you use SPLM sentiment lexicon in your research, please cite the above paper:

# Huffman-codes-

     In 1952 David A. Huffman the student of MIT discovered an algorithm called the “HUFFMAN CODING ALGORITHM” during work on his term paper assigned by his professor Robert M. Fano.The idea came in to his mind that using a frequency sorted binary tree we can able to find out the most efficient binary code. Huffman deny the major flaw of Claude Shannon Fano coding by building the tree from bottom up instead of from the top down.
     Data compression is one of the most important areas of computer science. It enables devices to transmit data with fewer bits (saving time and storage space). There is a lot of compression algorithm but we focus on lossless compression so in this regard Huffman algorithm is so cool and efficient algorithm in sort of smallest application. 
     It is a statistical compression method that converts characters into variable length bit strings and produces a prefix code. Most frequently occurring characters are converted to shortest bit strings; least frequent, the longest. Huffman use for image compression for example PNG ,JPG for simple picture of bird it also use MPEG whenever you watch movie or video in computer chances are that its image will be in MPEG format both these PNG MPEG and for text compression for example static and dynamic Huffman coding techniques.
 
Huffman coding is a lossless data compression algorithm. The idea is to assign variable-length codes to input characters, lengths of the assigned codes are based on the frequencies of corresponding characters. The most frequent character gets the smallest code and the least frequent character gets the largest code.
     The variable-length codes assigned to input characters are prefix codes, means the codes (bit sequences) are assigned in such a way that the code assigned to one character is not the prefix of code assigned to any other character. This is how Huffman Coding makes sure that there is no ambiguity when decoding the generated bitstream. 

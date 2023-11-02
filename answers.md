# CMPS 2200 Recitation 6
## Answers

**Name:** Jacob Hornung


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt       | 574592       | 826    | .0014375417
alice29.txt  | 176372858888 | 676374 | .0000038349
asyoulik.txt | 176372858888 | 606448 | .0000034384
grammar.lsp  | 110766728    | 17356  | .0001566896
fields.c     | 994580000    | 56206  | .0000565123

I don't know if I'm supposed to be this vague, but Huffman coding cost is a lot smaller (like insanely smaller) than Fixed-length coding. The ratio is therefore incredbily small, as Huffman coding is that much more efficient than fixed-length coding.

- **e.**

Because each character has the same frequency, the entire tree is perfectly balanced. This would mean that the huffman tree would have a size of log_2(n) where n is the number of unique characters in the document. This would be the same for all different documents, as as long as the documents have characters with the exact same frequencies the equation log_2(n) perfectly creates the huffman tree size.

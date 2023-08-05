A project on text file compression using Huffman encoding and decoding


![HuffmanAlgorithmGif](https://github.com/arfath11/Text_File_Compression_Me/assets/74487575/1765d0dd-e403-40c0-b020-b3c9b8f37f92)

The above pictorial representation clearly demonstrates the complete Huffman coding algorithm 
for the text = “Stressed-desserts”. 
Size of a file with this text =  17*1 = 17 bytes
Size of an encoded file = 1*S + 1*- + 2*d + 4*e + 2*r + 5*s + 2*t = 1*4 + 1*4 + 2*3 + 4*2 + 2*3 + 5*2 + 2*3 =  44 bits = 44/8
bytes = 5.5 bytes


Encoding 

1. Create a object of class EncodingHuffman 
2. pass the  filepath as the parameter
3. Call compression method on   the above object 

Decoding 
1. Run the Decoding Code
2. Pass the filepath of ur .bin file to be compressed
3. Make sure to have both .bin and .json file to be in the same folder

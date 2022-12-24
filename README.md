# Huffman_Coded_File_Compressor
> Huffman coding is a lossless compression algorithm. 
This program takes advantage of this and compresses .txt files. 
It can achieve an overall compression ratio of: 8 bits/5.32 bits, or about (1.5 : 1).
The main idea is to minimize the wighted expected length of code in file by means of assigning shorter codes to more often used characters.

### 1. To generate Compressor(archive) & decompressor(extract) use command:
```bash
make all
```

### 2. To compress a file (say "text.txt") use command:
```
./archive {{filename}}
```
eg. 
```
./archive text.txt
```

### 3. To decompress a compressed file (say "text.txt.compressed") use command:
```
./extract {{filename}}
```
eg. 
```
./extract text.txt.compressed
```

# burrow-wheeler
Burrows-Wheeler Compression Algorithm Implementation

Run followning command in /src folder
---------------------------
javac *.java
---------------------------

For compression
----------------------------------------------------------------------
java BurrowsWheeler - < $1 | java MoveToFront - | java Huffman - > $2
----------------------------------------------------------------------

For Decompression
----------------------------------------------------------------------
java  Huffman + < $1 | java MoveToFront + | java BurrowsWheeler + > $2
----------------------------------------------------------------------

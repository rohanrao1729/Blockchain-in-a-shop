# Blockchain-in-a-shop
<---------------****READ_ME***--------------->

What are all the files?
------------------------------
1.Start.java
Main program resides here
2.fxt.txt---|
            |
            v 
input transaction according to format:
first line contains an integer no of transactions(n)
for the next n lines
we have transactions of either of two types:
first type "1 amount sender".Here the assumption is receiver is Dexter(owner)
second type "2 amount sender receiver"
3.fotxt.txt
This is the Output file.
4.transactionGen.py
This file can be used to generate random number of transactions,the transactions generated here are put into ftxt.txt
 
How to execute?
------------------------------
->GenerateRandom input or give inputs:
To execute transactionGen.py
python transactionGen.py
->Main program is here
To execute Start.java file
Javac Start.java
java Start


How to check for immutablity?
-------------------------------
If some transactions are initially present and program is run you get last block hash printed in output file(fotxt.txt) and again when you change some transaction and run the program you can observe
that the hash value will be changed






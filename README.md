# Hadoop-HDFS-and-MapReduce:Word-Pair Count

The default input key for the TextInput format is the line number. 
In this homework , the required output is the count of word pairs. 

NOTE: punctuation will NOT count; so the words is ‘(1991)’ and ‘1991’are the same. Therefore, you must parse your file: remove all characters not in this set: [a-z, A-Z, 0-9] ; ‘the-cat’ and ‘the cat’ should be counted as the same pair.     

e.g. line:     

Input:(k,v) = (1,“the cat in the hat is the best cat in the hat”)  
Output:(k2,v2) = (“the cat”, 1), (“cat in”,2),(‘in the’,2),(‘the hat’,2’),(‘hat is’,1), etc     

If the line contains a single word, then that becomes the ‘pair’.     

For this code, use the input file: adventures.txt and output the result as part-00000.txt

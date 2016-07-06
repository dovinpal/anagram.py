### Knowbigdata.com

#### anagram.py


#!/usr/bin/python
import fileinput

for line in fileinput.input():
	
	#Evaluating each word
	for word in line.split():
		print ''.join(sorted(list(word))), "\t1"

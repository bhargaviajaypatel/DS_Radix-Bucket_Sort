# DS_Radix-Bucket_Sort
When we have a list of sorted names, the radix is 26 (or 26 buckets) because there are 26 letters of the alphabets.
Observe that words are first letter of the name.
That is, 26 classes are used to arrange the names, where the first class stores the name that begins with 'A', the second class contains names with 'B', so on and so forth .
During the second pass, names are grouped according to the second letter.
After the second pass, the names are sorted on the first two letters.
This process is continued till nth pass, where n is the length of the names with maximum letters.
After every pass, all the names are collected in order of buckets.
That is, first pick up the names in the first bucket that contains names beginning with 'A'. 
In the second pass collect the names from the second bucket so on and so forth.
When radix sort is used on integers, sorting is done on each of the digits in the numbers.
The sorting procedures proceeds by sorting the least significant to most significant digit.
When sorting numbers, we will have ten buckets, each for one digit (0,1,2...,9) and the number of passes will depend on the length of the number having maximum digits. 

# CODECHEF
## Competitve Coding
### Q1 -> STRRCT
[Link to Q1 code](https://www.codechef.com/viewsolution/1048637129)
\
The logic I have used for this question is to check if both strings have the same set of characters, if yes, 2 <abbr title="yeah its technically a dictionary">**Hashmaps**</abbr> are created.
The s1 is supposed to be multiple permutations of s2 hence we can find couunt of each letter in s1 and s2 and get a ratio by s1/s2 for each letter
Then the number of unique ratios is counted , if 1 , then its a Yes <abbr title="If more than 1 ratio exists then its invalid as is just a jumbled version of n times self concatenated s2">**else**</abbr> No.

### Q2 -> POWTWOADD
[Link to Q2 code](https://www.codechef.com/viewsolution/1048818317)\
Here Ihave used python's inbuilt binary functio to get the number as binary and just count the ones , as only count of non zero 2 powers is asked.

### Q3 -> STAIRCASE
[Link to Q3 code](https://www.codechef.com/viewsolution/1048637129)\
Here understanding question visually was the key , the chef goes left to right in the <abbr title="I have used vector">*array*</abbr> and he only takes sequential numbers of which already he have starting from 1 , if he was able to fetch the complete array , within 2 trips , Yes else No

### Q6 -> BTWSXOR
[Link to Q6 code](https://www.codechef.com/viewsolution/1048488035)\
Here it was just a matter of checking sum and xor value of each combination of pairs in the given array 

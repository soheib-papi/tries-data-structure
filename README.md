# <span style="color: red;">Tries</span>
### All the readme text and code in this repository are taken from the course [The Ultimate Data Structures & Algorithms Part 2](https://codewithmosh.com/p/data-structures-algorithms-part-2) created by [Mosh Hamedani](https://codewithmosh.com/)
#### Dear Mosh, you are a pride of Iranians.


#### **Believe me, tries are one of the most useful and fascinating data structures.**
Tries are another kind of trees, **but they're not binary trees**. 
So **each child can have several nodes**. The name trie actually comes from **retrieval**. 
Some people say trie others call it trees. The other names for
tries are digital ray dex or prefix trees. 
**We use tries to implement auto completion.**
For example, when you type a search query on Google, you'll see Google quickly 
suggesting a few phrases that start with what do you have typed? 
That I'm not sure if they have implemented this using tries, 
but auto completion is one of the key applications of tries. 
I might ask why not use an area of strings and return the items that start 
with a search query for two reasons. The first reason is that if you have a
large number of words or search queries, this array is going to waste a lot
of space because a lot of words have the same prefix. For example, pig, 
picky pickle, picture picnic, all start with pic. That is the prefix the
reason is that looking at words that start with a prefix using arrays is 
relatively slow, we have to go through every word and check to see if the word 
starts with our prefix. Now there are ways we can optimize this. 
But overall, arrays are not ideal for solving this problem. 
That's where we use tries, tries allow us to store thousands or even 
millions of words in minimal space and provide super fast look ups.

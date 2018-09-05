**Problem**

To create a prototype set of keywords for search campaigns for sofa section of a retailer of furniture.
Client requests to create keyword for the following products:
1. sofas
1. convertible sofas
1. love seats
1. recliners
1. sofa beds


**Analysis**

So to approach this problem we need to figure out a set of words which will provide a good estimation for a searched query.
for example: if we choose the words set as ['buy', 'discount'] then the user's search query may have the following phrase,
'buy sofas' or 'discount on sofas'.

This is just a first step approach using a set of predetermined words. But this can be improved with some data mining technique where we can learn about user behaviour and choose a set of perfect words.

**Final Result**

Final result will produce a Pandas DataFrame and saved as a csv file. sample dataframe as below:

Campaign | Ad Group	| Keyword	| Criterion Type
-------- | -------- | ------- | --------------
camp1    | ad_grp_1 | k_word1 | exact
camp1    | ad_grp_2 | k_word2 | phrase
camp1    | ad_grp_2 | k_word1 | exact

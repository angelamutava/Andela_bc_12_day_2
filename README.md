# Andela_bc_12_day_2
##Finding Maximum and Mininum value in a list
This is a function that returns the largest and the smallest number in a list.If both values are equal it returns the length of the list.
######For example the following statements will return the below:
```
print find_max_min([1, 2, 3, 4, 5])

print find_max_min([2,2])
```
######Result
```
[1,5]
[2]
```
## Word Count
This is a function that returns the count of each word in a string.It returns the word as  the key in a dictionary and the count as the value.
######For example the following statement will return the below:
```
print word_count("angela angela mutava")
```
######result
```
{"angela":2, "mutava":1}

```
##Twitter Streaming API and the Tweepy library
This is a simple command line application that takes advantage of the Twitter streaming API to get tweets with the keyword andela,python and bootcamp.
To get started with the API:
* create a twitter account.
* login to the account.
*Get the api keys and the tokens respectively.<br/>


The above credentials will be needed in the twitter.py file.<br/>
To install the tweepy library to your virtual environment.<br/>
######Requirements for the virtual env include
*oauthlib==2.0.0
*requests==2.11.1
*requests-oauthlib==0.7.0
*six==1.10.0
*tweepy==3.5.0


######Run the command
```
pip install tweepy
```  
You can as well clone the repository 
######clone
```
$ git  clone https://github.com/anonymousme/Andela_bc_12_day_2
```  
Run the tweet.py file with the command below.It will generate some tweets on the command line.To store the tweets in a txt file run the command.
```
python tweet.py
```
```
python tweet.py > tweets.txt
```      



##Guide
To gain practical experience of how the functions work you can clone the repository. With python installed in your machine navigate to the appropriate folder on command line and run python filename e.g word_count.py
######clone
######$git clone https://github.com/anonymousme/Andela_bc_12_day_2

######Tests
To demonstrate TDD every function has some tests that it should pass in the respective test files. 


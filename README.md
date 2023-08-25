# The Reverse Numbers Trick

So, i was trying to prove the Reverse Numbers Trick from this youtube short: [https://www.youtube.com/watch?v=7RSqBuZzthk](https://www.youtube.com/watch?v=7RSqBuZzthk)

## How it works

You take any number, for example 174. You reverse the number and add the numbers together. So 174 + 471 = 645. And you repeate the process until you get [palindrome](https://en.wikipedia.org/wiki/Palindrome "explanation"). 

---

174 + 471 = 645

645 + 546 = 1191

1191 + 1911 = 3102

3102 + 2013 = 5115

---

5155 is palindrome.

## The problem

In the video Vsauce2 said that it doesn't work with number 196. Witch is teoretically true.

I was curious if there are more of those numbers that this trick doesn't work on. 

I found out that there are a lot of numbers that this trick doesn't work on. The full list is in [data.txt](data.txt).

## How I checked if it works

So i tried every number up to 5006254.

The way it works is that the computer repeats this process until the number is greater than one [quinsexagintillion](https://googology.fandom.com/wiki/Quinsexagintillion).

If it is greater and has not yet reached a palindrome, it is counted as invalid.

# DEVELOPER CHALLENGES

This repos contain a series of level 100 and level 200 challenges.

If you have any questions or need any help with the challenges, don't hesitate to reach out to hello@bluefragments.com.

## challenge-101

Create a function that takes an array of numbers and return both the minimum and maximum numbers, in that order.

Examples:  
FindMinMax([1, 2, 3, 4, 5]) ➞ [1, 5]  
FindMinMax([2334454, 5]) ➞ [5, 2334454]  
FindMinMax([1]) ➞ [1, 1]  

## challenge-102

Create a function that accepts a string of a person's first and last name and returns a string with the first and last name swapped.

Examples:  
NameShuffle("Donald Trump") ➞ "Trump Donald"  
NameShuffle("Rosie O'Donnell") ➞ "O'Donnell Rosie"  
NameShuffle("Seymour Butts") ➞ "Butts Seymour"  

## challenge-103

Create a function that returns true if an input string contains only uppercase or only lowercase letters.

Examples:  
SameCase("hello") ➞ true  
SameCase("HELLO") ➞ true  
SameCase("Hello") ➞ false  
SameCase("ketcHUp") ➞ false  

## challenge-104

An isogram is a word that has no duplicate letters. Create a function that takes a string and returns either true or false depending on whether or not it's an "isogram".

Examples:  
IsIsogram("Algorism") ➞ true  
IsIsogram("PasSword") ➞ false  
// Not case sensitive.  
IsIsogram("Consecutive") ➞ false  

## challenge-105

Create a function that takes a number (from 1 to 12) and returns its corresponding month name as a string. For example, if you're given 3 as input, your function should return "March", because March is the 3rd month.

Examples:  
MonthName(3) ➞ "March"  
MonthName(12) ➞ "December"   
MonthName(6) ➞ "June"  

## challenge-106

Create a function that takes a string and replaces each letter with its appropriate position in the alphabet. "a" is 1, "b" is 2, "c" is 3, etc, etc.

Examples:  
AlphabetIndex("Wow, does that work?") ➞ "23 15 23 4 15 5 19 20 8 1 20 23 15 18 11"  
AlphabetIndex("The river stole the gods.") ➞ "20 8 5 18 9 22 5 18 19 20 15 12 5 20 8 5 7 15 4 19"  
AlphabetIndex("We have a lot of rain in June.") ➞ "23 5 8 1 22 5 1 12 15 20 15 6 18 1 9 14 9 14 10 21 14 5"  

## challenge-201

Usually when you sign up for an account to buy something, your credit card number, phone number or answer to a secret question is partially obscured in some way. Since someone could look over your shoulder, you don't want that shown on your screen. Hence, the website masks these strings.

Your task is to create a function that takes a string, transforms all but the last four characters into "#" and returns the new masked string.

Examples:  
Maskify("4556364607935616") ➞ "############5616"  
Maskify("64607935616") ➞ "#######5616"  
Maskify("1") ➞ "1"  
Maskify("") ➞ ""  

## challenge-202

Create a function that takes a positive integer and returns a string expressing how the number can be made by multiplying powers of its prime factors.

ExpressFactors(2) ➞ "2"  
ExpressFactors(4) ➞ "2^2"  
ExpressFactors(10) ➞ "2 x 5"  
ExpressFactors(60) ➞ "2^2 x 3 x 5"  

## challenge-203

Create a function that finds a target number in a list of prime numbers. Implement a binary search algorithm in your function. The target number will be from 2 through 97. If the target is prime then return "yes" else return "no".

Examples:
int[] primes = { 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97 }  
IsPrime(primes, 3) ➞ "yes"  
IsPrime(primes, 4) ➞ "no"  
IsPrime(primes, 67) ➞ "yes"  
IsPrime(primes, 36) ➞ "no"  

## challenge-204

Create a function to return the amount of potatoes there are in a string.

Examples:  
Potatoes("potato") ➞ 1  
Potatoes("potatopotato") ➞ 2  
Potatoes("potatoapple") ➞ 1  

## challenge-205

Create two functions that take a string and an array and returns a coded or decoded message.

The first letter of the string, or the first element of the array represents the Character Code of that letter. The next elements are the differences between the characters: e.g. A +3 --> C or z -1 --> y.

Examples:  
Encrypt("Hello") ➞ [72, 29, 7, 0, 3]  
// H = 72, the difference between the H and e is 29 (upper- and lowercase).  
// The difference between the two l's is obviously 0.  
Decrypt([ 72, 33, -73, 84, -12, -3, 13, -13, -68 ]) ➞ "Hi there!"  
Encrypt("Sunshine") ➞ [83, 34, -7, 5, -11, 1, 5, -9]  

# Quote-Guessing-Game
we will scrape a quote and details of the author from this site http//quotes.toscrape.com using python framework called BeautifulSoup and develop a guessing game using different data structures and algorithm.

The user will be given 4 chances to guess the author of a famous quote, In every chance the user will be provided with a hint which can be the author’s birth date, first name’s first letter, second name’s first letter, etc. On successfully guessing the author, a message is printed and if the user fails to guess the answer even after all the 4 chances then again a message is printed along with the answer.

<br>Approach
Import module
      1.requests help us grab the page, when the response is received it is stored in the form of a string
      2.bs4 library is used to create beasutifulSoup object.
      3.csv library helps reading and writing CSV files using python
      4.sleep function from time module helps add delay in the execution of the program.
      5.choice function from random module returns a random element.
Create a list to store values scraped
Scrape the details from this link: http//quotes.toscrape.com
Extract data
Game logic
Return random items from the dictionary created
Set number of guesses
Write message for success and failure
Keep giving hints until either number of chances reach zero or the user gets it right
Time Complexity: 
The time complexity of this code is O(N) because the while loop is iterating over quotes list N times.

Space Complexity:
The space complexity of this code is O(N) because the all_quotes list is storing N number of elements.

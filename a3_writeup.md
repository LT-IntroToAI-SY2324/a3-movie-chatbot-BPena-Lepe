# Assignment 3 - Writeup

Assignment 3 is all about creating this natural language query system.  In order to do so, you have to write a lot of functions to retrieve infomation.  You will also have to write a function to return answers from a pattern-action list.  There is a lot of work to accomplish in this assignment, but this portion is intended for you to write about what you accomplished.

## Reflection Questions
1. In your own words describe the `search_pa_list` function.
The search_pa_list function returning a value that would answer the quesiton by using the match funciton which matches the source to a pattern. If the source doesn't fit with a pattern it says that it doesn't understand, and when the question matches a pattern but there is no data it says that it has no answers.

2. What movie did you add to the `movies.py` file?  What year was it made? Any specific reason you added that movie?
I added Silence of the Lambs from 1991 to the movies.py file as I've heard its a great horror movie and I'm hoping to watch it this halloween.

3. What pattern / action did you add to the paList data structure?  Why do you think that is a useful pattern / action?
I added "what movie has % acted in" for title_by_actor, because I feel that that question flows more naturally compared to "in what movies did % appear".

4. What is chatbot would you create that would be like this?  Describe why you would create it and what it would do.
I would create an NBA chatbot that would give me data on player's points, rebounds, and assists. I would create it because I like basketball and follow the NBA a bit.

5. What was the most difficult portion of this assignment?
The most difficult portion was getting started on the title by year function as it took some thought to get it to work and all the other functions were similar to it.

6. Did you write a new assert for your pattern action?
 Yes I wrote an assert for director by title using silence of the lambs as the test element.



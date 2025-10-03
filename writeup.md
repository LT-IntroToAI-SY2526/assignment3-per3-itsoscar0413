# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
# I learned how to match user input with patterns using the signs like "_" and "%". I also learned how to add my own information into a database. In this assignment I added my own movie, and it was easy to update the code to make it work, so I also learned about how code is dependent on each other, and if you update something that affects other code, you need to fix it to make the code work again.

2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
# The chatbot reads the user’s question and checks if it matches any pattern it knows. If it finds a match, it runs the right code to search the movie list and gives an answer. If it doesn’t understand the question, it says so.

3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
# Some real world applications in which this could be useful for is a personal assistant, a customer service chatbot or even something which helps store information into databases and can be referred to. For practical use, I could add acronyms and other common words used in phrases to allow the database to be used more often because it can match prompts.
Start: How does it respond

1)My mother and I talked last night.

	The response to this is "tell me more about your family"

2)I said no!

	The response to this is "Why so Negative?"

3)The weather is nice.

	The response to this is "Do you really think so?"

4)Do you know my brother?

	The response to this is also "Why so Negative?"

Exercises:

1)Pick three more keywords, such as “no” and “brother” and edit the getResponse method to respond to each of these. Enter the three keywords and responses below.

Keyword                                              Response

music                                                I like trap music
question                                             I can answer some questions
friend                                               Can I be your friend?

2) What happens when more than one keyword appears in a string? Consider the string “My mother has a dog but no cat.” Explain how to prioritize responses in the reply method.

	When I enter the above statement I get the response for the part of the code which says "no". After looking at my code and experimenting with the reply method i workede out that you can prioritize the responses by the order they are in the if statement. For example if the reply for dog was first in the if statement, that is the response you would get as that is the first one to be checked for.

Questions:

1) What happens when a keyword is included in another word? Consider statements like “I know all the state capitals” and “I like vegetables smothered in cheese.” Explain the problem with the responses to these statements.

	When I entered "I like vegetables smothered in cheese." I was greeted with "Tell me more about your family." This is because of the word "mother" included in "smother". I experienced the same thing with the other statement and the "no" in "know"
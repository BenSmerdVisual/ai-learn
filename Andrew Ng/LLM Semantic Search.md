## Keyword Search
- Good for searching through LLM based on specific keywords
- Checks how many words are in common between the query and the responses, it can then retuyrn the one with most common words
	- **Lexical search**- a forumla that looks at the count of the common words that are an exact match 
	- The search system will have a document archive that was processed beforehand and then this is matched up based on the most common word result
	- It does a retriebval and reranking to find the results and will check the words in each document to see which has the most common results to the keywords
	- Bad when there are incorrect words but same context for what they want
## LLM Embeddings
- Grouping of words based on some sort of similarities (eg fruits, transport, sports) and this gives them a specific set of numbers based on the groupings of words and where they may sit across all posibble words
- Can have embeddings for sentences as well, and when sentences or words are similar then their numbers are closer together
- Based on the similarities of sentences with the embedding scores, it's easier to match a question with a response as the sentence will most likely be similar, eg ("Where does the bear live?"=> "The bear lives in the woods") (this is an example for a very small sample set as there would be even closer related responses based on the embedding score)
- Sentences are closer to each other based on the similar meaning

## Dense Retrieval
- Can be multilingual and take a query in another language and return in a different language as well
- **Nearest neighbour library**- Returns a scoring mechanism of how close the results are and this means the lowest distance is the "closest" to the query

## ReRank
- Improves the dense retrieveal and keyword search
- Because dense retrieval just gets the ones that are closest by rank, however thats based on the keywords and there may be more keywords however the answer may be wrong based on the wording or just wrong in general
- **Relevance**- get a relevance score based on a number which determines how relevant the response is to the query
- The ReRank is trained on many queries with correct answers and many queries with wrong answers, and this gives it more training to be able to determine the relevance score of the responses to the query
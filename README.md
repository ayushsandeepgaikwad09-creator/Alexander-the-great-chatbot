# Alexander the Great Chatbot

A command-line chatbot that answers in character as Alexander the Great — his birth, family, teachers, battles, empire, and death, plus some of his (reputed) quotes.

## How it works
The bot checks whether any word or phrase you type matches a keyword in a dictionary of topics, then returns one of several possible responses at random using Python's `random` module. If nothing matches, it gives an in-character "I don't know that" reply instead of crashing or going off-topic.

## Built with
- Python 3 (dictionaries, functions, loops, the `random` module)
- No external libraries or AI model — just core Python

## Example
Alexander: Greetings! I am Alexander the Great. Ask me of my life and conquests. Type ‘bye’ to leave my court.
You: tell me about your horse
Alexander: No one else could tame Bucephalus. I rode him from Macedon to India.

## What I'd improve next
Keyword matching is simple but has real limits — it can misfire on unrelated phrases, and won't catch questions worded unusually. A natural next step is a proper NLP approach (intent classification) instead of plain substring matching.


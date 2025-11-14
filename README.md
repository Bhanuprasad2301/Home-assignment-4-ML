Name: Bhanu prasad Dogiparthy
700: 700762758
1)
The code takes a sentence and breaks it into individual words.
It removes stopwords like the, in, while because they don’t add real meaning.
It filters out any punctuation and keeps only alphabetic words.
It uses POS tagging to check whether each word is a noun, verb, adjective, etc.
It applies lemmatization, which means turning words into their root form playing → play
It creates a clean list of meaningful words that are easier for ML models to understand.
It finally picks out only nouns and verbs, because they carry the most important information.






2)
The code splits the text into words to start analyzing the sentence properly.
It uses POS tagging to label each word noun, verb, proper noun, etc.
It performs Named Entity Recognition NER to detect names, companies, and places.
It identifies entities like Chris ,person, Apple organization, California, location
It prints these named entities in a clear format so you can easily see what was detected.
It checks if pronouns like he, she, they appear in the sentence.
If pronouns are found, it prints a warning because the sentence may be confusing about who the pronoun refers to.

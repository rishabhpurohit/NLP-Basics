# TEXT NORMALISATION TECHNIQUES


## Stemming and Lemmatization are Text Normalization (or sometimes called Word Normalization) techniques in the field of Natural Language Processing. 



But what is normalization of text? Well, normalization is getting rid of inflection from sentence. Now, what is inflection? 



As it is in wiki, “In grammar, inflection is the modification of a word to express different grammatical categories such as tense, case, voice, aspect, person, number, gender, and mood. An inflection expresses one or more grammatical categories with a prefix, suffix or infix, or another internal modification such as a vowel change.”



Example. Consider the words studying, studies, studied. All three relate to their root study. Words such as am, are, is all relate to their root form be. Similarly brighter, brightest both relate to the root word bright. Spotchamp’s, Spotchamps, Spotchamps’ relate to their root Spotchamp.



Now consider the following sentence.

“Spotchamps are studying smart for a brighter career “



A normalization of this sentence would be like this.

Spotchamp be study smart for a bright career.



Stemming and Lemmatization are widely used techniques in natural language processing. Can you give me an example where you see the usages of word normalization? You do it every day. It’s used in Google search. For an example, when you search for the word house, you also see search results for houses, housing etc. Because both the words relate to their root, house.



Stemming is the process of bringing down a word to its root, or to its simpler form, which isn’t necessarily a word on its own. So the example of Google search that we discussed in our earlier video, is an example of Stemming. Stemming makes it possible for us to get information about bank, banks, banking, banker etc when we just search with the word bank. Because all words banks, banking, banker etc have their root at the word bank. This is a very powerful technique in natural language processing.

Lemmatization is the process of converting a word to its base form. The difference between stemming and lemmatization is, lemmatization considers the context and converts the word to its meaningful base form, whereas stemming just trims a word, such as by removing its prefix, suffix etc, to its root form. As I said earlier Stemming often lead to incorrect meanings and spelling errors. On the other hand, Lemmatization considers the context of the word. So it is essential for Lemmatization to have detailed dictionaries which the algorithm can look through to link the form back to its lemma.

# Multiword-Metaphor Detection Project

We aim to build a model that can accurately detect metaphorical language, whether it appears as a single word (e.g., My lawyer is a *shark*.) or as a multiword expression (e.g., That woman is a *wilting violet*.).

While recent automatic metaphor detection systems (e.g., DeepMet, MOH-X-based classifiers) have achieved impressive performance, they typically operate at the token level and focus on identifying metaphors in single words, such as isolated verbs or nouns. This limitation largely stems from how existing models tokenize and represent text, treating words independently rather than as semantically unified phrases.

However, this approach poses a significant challenge. Many metaphorical expressions are not confined to single words but span entire phrases, or even full clauses, whose figurative meaning arises from their combined use. Identifying only word-level metaphors fails to capture these richer, more holistic metaphorical structures.

To address this, our project aims to:

1. Develop or adapt a parser that identifies multiword expressions (MWEs) of various types, including noun phrases and verbal phrases, rather than parsing text into standalone tokens.

2. Compare the literal meaning of these MWEs with their contextual meaning to determine whether the expression is used metaphorically in context.

By leveraging MWE identification techniques and contextualized semantic models, our system will be designed to recognize metaphorical meaning at the phrase level, bringing us closer to human-like metaphor understanding in NLP.



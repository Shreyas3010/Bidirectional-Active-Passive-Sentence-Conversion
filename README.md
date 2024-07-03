# COMP6591 - Introduction to Knowledge-Base Systems
# Utilizing Prolog for converting between active sentence and passive sentence with three-steps conversion

## Team:
- Shreyas Patel
- Anurag Shekhar

The primary goal of this project was to develop an automated solution for converting active sentences to passive sentences using Prolog and Natural Language Processing (NLP) techniques. The system employed a three-step process based on Definite Clause Grammar (DCG) to identify the input sentence representation, determine the corresponding target sentence representation, and generate the output sentence. Additionally, the project aimed to improve efficiency and conciseness by categorizing the 12 different tenses into four groups based on the presence of auxiliary verbs, which significantly reduced overall code complexity and effectively handled all possible cases of sentence conversion.

* `convertible.pl`: implementing DCG rules for 1st and 3rd steps in the three-steps conversion, as well as other rules including lexicon.
* `convert.pl`: implementing the three-steps conversion and its 2nd step.
* `testSuite.pl`: providing commands for user interaction. Users do not need to type the input sentence as a list (like `[the, man, buys, an, apple]`) but can type the sentence in the common way (directly type: `the man buys an apple`) by using two commands: `active` and `passive`. Moreover, users can easily check the correctness of the program by using two test suite commands: `activeTestSuite` and `passiveTestSuite`.

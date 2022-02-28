# Text Analysis Overview


A little intro to the text analysis methods

<br />

[Data Preparation](../data_prep/) &emsp;&emsp; [Useful Methods](../methods/) &emsp;&emsp; [Research Objects](../research_objects/)

<br />

### Understanding Text as Data

The term word is problematic. It is well-known to linguists that phonological words (defined by sound patterns), syntactic words (defined by combinatorial possibilities) and orthographic words (defined by the conventions of a writing system) do not always coincide. And even when we are only looking at written material, there are problems. How many words are there in this sentence?

<center><i>The cat sat on the mat </i></center>
<br />
One answer is that there are six words; that is, there are six groups of characters which are separated according to typographical convention. But there is another answer. There are five words, that is five distinct sequences of characters and one of those sequences (the) occurs twice. The terms standardly used to make this distinction are type and token. Tokens are instances of types, therefore if we count tokens, we count without considering repetition, while if we count types, we do consider repetition.

There is a further distinction we may need to make which we can see if we consider another question: Are cat and cats the same word? They are distinct types, and therefore must also be distinct as tokens. But we have an intuition that at some level they are related, that there is some more abstract item which underlies both of them. This concept is usually referred to as a lemma (there is more about this concept on the Data Cleaning page).



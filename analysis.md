# Analysis

## Layer 1, Head 8

This attention head seems to pay attention to the end of the sentence. Many tokens attend strongly to the `[SEP]` token, especially when there is no obvious word to focus on.

Example Sentences:

* Then I picked up a [MASK] from the table.
* We turned down a narrow lane and passed through a small [MASK].

## Layer 7, Head 5

This attention head seems to pay attention to adjectives and the nouns that follow them. In several examples, adjectives attend strongly to the noun they describe.

Example Sentences:

* The small [MASK] was empty.
* She bought a beautiful [MASK] yesterday.

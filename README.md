# Part3-module-5
NLP and Sequence Modeling Mini Project

Why Convert Text into Vectors?

Machine learning models cannot understand raw text directly.
Text must be converted into numbers because:

models operate on mathematical computations
vectors represent word importance/patterns
numerical representations help models learn relationships between words

Examples:  Bag of Words → word frequency
________________________________________________________________________________
Why Sequence Models?

Traditional models:ignore word order

Sequence models:understand sentence flow and context

Example:
"not good" ≠ "good"
________________________________________________________________________________
Why RNNs Struggle with Long-Term Dependencies ?

RNNs process text one word at a time.

Problems:
earlier information gradually fades
vanishing gradient problem
difficult to remember long sentences

Example:
"The phone I bought last month ... stopped working"

The model may forget important earlier words.
___________________________________________________________________________________
How LSTMs Help with Memory ?

LSTMs introduce:

memory cells
gates

These mechanisms help:

retain useful information
forget irrelevant information
learn long-range dependencies better than vanilla RNNs
_____________________________________________________________________________________
What Attention Solves ?

Attention allows models to:

focus on important words
dynamically assign importance weights

Instead of compressing everything into one hidden state, attention selectively looks at relevant parts of the sequence.
______________________________________________________________________________________
Why Transformers Are Important

Transformers:
process sequences in parallel
use self-attention
capture long-range dependencies efficiently

Advantages:
faster training
better scalability
superior NLP performance

Modern Generative AI models such as:
GPT
BERT
T5
____________________________________________________________________________________________

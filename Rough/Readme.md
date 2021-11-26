## Intro

Good evening sir //
Good evening to the faculty members and my teammates present here. 
I am Bhukya Vasanth Kumar. 
We’re here to explain to you about our project ‘ Abstractive Text summarisation ‘ briefly. 

So basically, Abstractive Text Summarisation is the process of generating a short and precise summary that captures the most important terms from the source text / input. 

And it’s very important to know what a summary is. It’s a text that is produced from one or more texts, that conveys important information in the original text(s), and that is no longer than half of the original text(s) and usually, significantly less than that.

There are two different approaches, namely Extractive Summarisation and Abstractive Summarisation. In Extractive text summarisation, let’s say there is a passage with multiple sentences. This model picks up important sentences and puts them in the summary. It doesn’t change anything. You can say that the summary generated is a subsequence of the given source text.  

Abstractive text Summariser generates new sentences, possibly rephrasing or using the words that were not in the original text in a human readable format. This ensures that the core information is conveyed through the shortest text possible. 

This work is based on the Abstractive Summarisation which is quite advanced than the former. 


## Why this Project?

In recent years, availability of the data generated has increased to an exponential scale. Summarisers make it simpler for users to summarize the data without pursuing it totally
Also the need for summarization can be seen in various purpose and in many domain such as news articles summary, email summary, short message of news on mobile, and information summary for businessman, government officials, researchers online search through search engine to receive the summary of relevant pages found, medical field for tracking patient’s medical history for further treatment. 

1. Summarization helps to understand required information in less time i.e reduces reading time.
2. Used in many domains such as new articles summary and medical field for tracking patient’s medical history.
3. It enables you to focus on key words and phrases of an assigned text that are worth noting and remembering. 

## Why is it Challenging?
 
Automatic text summarization is very challenging, because when we as humans summarize a piece of text, we usually read it entirely to develop our understanding, and then write a summary highlighting its main points. Since computers lack human knowledge and language capability, it makes automatic text summarization a very difficult and non-trivial task.
A good summary should also consist of other aspects such as coverage, nonredundancy, cohesion, relevancy, and readability.


## Seq2Seq 
It is a method of encoder-decoder based machine translation and language processing that maps an input of sequence to an output of sequence with a tag and attention value. The idea is to use 2 RNNs that will work together with a special token and try to predict the next state sequence from the previous sequence.

Although simple encoder-decoder models produce competitive results, many researchers have proposed additional improvements over these sequence-to-sequence models, e.g., using an attention-based model over the input, pointer-generation models, and self-attention models. However, such seq2seq models suffer from two common problems: 1) exposure bias and 2) inconsistency between train/test measurement. Recently, a completely novel point of view has emerged in addressing these two problems in seq2seq models, leveraging methods from reinforcement learning (RL). In this survey, we consider seq2seq problems from the RL point of view and provide a formulation combining the power of RL methods in decision-making with sequence-to-sequence models that enable remembering long-term memories. 



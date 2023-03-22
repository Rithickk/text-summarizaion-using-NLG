##Abstractive Text Summaraization using NLG (Natural Language Generation)

We come across several different types of documents for various purposes.
Creating a summary from a given content is a process that everyone participates
in and which is very useful for people to quickly get the relevance of the
document for their intended needs. Abstractive summarization involves
paraphrasing the given content using novel sentences generating a summary of a
text from its main ideas, not by copying verbatim most salient sentences from
the text. This is an important and challenging task in natural language
processing. This project uses transformers (transformer is a deep learning model
that adopts the mechanism of self-attention, differentially weighting the
significance of each part of the input data) and transfer learning concepts to
phrase the summaries and gets inputs not only as text but also in audio format.
This project focuses on summarizing archived audio files that are lengthy for
ease of access. A T5 model was used to summarize the text. T5 is an encoder-
decoder model and converts all NLP problems into a text-to-text format. The
supported input file formats are txt, docs, pdf, mp3 and wav. The outputs are
produced in text format. It is to be noted that the input audio file must be clear
of background noise and voice overlapping. This project is a successful
implementation of T5 model in abstractive text summarization

# Text Summarization
**Automatic summarization** is the process of shortening a text document with software, in order to create a summary with the major points of the original document. Technologies that can make a coherent summary take into account variables such as length, writing style and syntax.

Automatic data summarization is part of the real machine learning and data mining. The main idea of summarization is to find a subset of data which contains the "information" of the entire set. Such techniques are widely used in industry today. Search engines are an example; others include summarization of documents, image collections and videos. Document summarization tries to create a representative summary or abstract of the entire document, by finding the most informative sentences, while in image summarization the system finds the most representative and important (i.e. salient) images. For surveillance videos, one might want to extract the important events from the uneventful context.

There are two general approaches to automatic summarization: extraction and abstraction. Extractive methods work by selecting a subset of existing words, phrases, or sentences in the original text to form the summary. In contrast, abstractive methods build an internal semantic representation and then use natural language generation techniques to create a summary that is closer to what a human might express. Such a summary might include verbal innovations. Research to date has focused primarily on extractive methods, which are appropriate for image collection summarization and video summarization.

In this Jupyter notebook, TextRank algorithm for extractive text summarization is implemented using Google's PageRank search algorithm to generate corelations among sentences.

## Libraries Used
- [Numpy](http://www.numpy.org)
- [Matplotlib](https://matplotlib.org)

## Algorithms and Concepts
- TextRank
- [PageRank](https://en.wikipedia.org/wiki/PageRank)
- [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity)

## How to run
- `git clone https://github.com/amanraj209/text-summarization.git`.
- Install the required libraries using pip, virtual environment or conda.
- Run `jupyter notebook` in your terminal.

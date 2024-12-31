# Text-Summarization-Tool

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: P.Priyadharshini

**INTERN ID**: CT08FAU

**COURSE**: Artificial Intelligence

**BATCH DURATION**: DECEMBER 20th,2024 to JANUARY 20th,2025

**MENTOR NAME**: NEELA SANTHOSH KUMAR

**DESCRIPTION**
Automatic text summarization refers to a group of methods that employ algorithms to compress a certain amount of text while preserving the text's key points. Although it may not receive as much attention as other machine learning successes, this field of computer automation has witnessed consistent advancement and improvement. Therefore, systems capable of extracting the key concepts from the text while maintaining the overall meaning have the potential to revolutionize a variety of industries, including banking, law, and even healthcare.

Types of Text Summarization
There are typically two basic methods for automatic text summarization:

Extractive summarization
Abstractive summarization
Extractive Summarization
Extractive summarization algorithms are employed to generate a summary by selecting and combining key passages from the source material. Unlike humans, these models emphasize creating the most essential sentences from the original text rather than generating new ones.

Extractive summarization utilizes the Text Rank algorithm, which is highly suitable for text summarization tasks. Let's explore how it functions by considering a sample text summarization scenario.

Utilizing TextRank Algorithm for Extractive Text Summarization
The implementation of TextRank offers a spaCy pipeline as an additional feature. SpaCy is an excellent Python library for addressing challenges in natural language processing. Additionally, you need pytextrank, a spaCy extension that effectively implements the TextRank algorithm. It is evident that the TextRank algorithm can produce reasonably satisfactory results. Nevertheless, extractive summarization techniques merely provide a modified version of the original text, retaining certain phrases that were not eliminated, instead of generating new text (new data) to summarize the information contained in the original text.

Prerequisite
Spacy

To Install the Spacy and Dowload the English Language Dependency run the below code in terminal

!pip install spacy
To install the english laguage dependency

!python3 -m spacy download en_core_web_lg
TextRank

To Install the TextRank

!pip install pytextrank
Text Summarizations
This code uses spaCy and PyTextRank to automatically summarize a given text. It first installs the required packages, downloads a spaCy language model, and loads the model with the TextRank summarization pipeline. It then processes a lengthy text and generates a summary of the text's key phrases and sentences. The summary is limited to 2 phrases and 2 sentences.

Conclusion
As we come to a conclusion, the future of text summarization seems bright. We are working to uncover the possibility of summarizing text with even more accuracy and human-like intuition by using extractive and abstractive approaches, as well as potent models like PEGASUS. This journey is continuing to transform how we condense massive volumes of information into succinct, insightful insights, and it promises a future in which we will be able to distil knowledge more effectively than before. The development of text summarization is evidence of the ever-expanding potential of AI and its dedication to improving human comprehension.

Are you passionate about data and looking to make one giant leap into your career? Our Data Science Course will help you change your game and, most importantly, allow students, professionals, and working adults to tide over into the data science immersion. Master state-of-the-art methodologies, powerful tools, and industry best practices, hands-on projects, and real-world applications. Become the executive head of industries related to Data Analysis, Machine Learning, and Data Visualization with these growing skills. Ready to Transform Your Future




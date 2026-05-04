# NLP-notes
📘 NATURAL LANGUAGE PROCESSING (NLP) — NOTES

🔹 What is NLP?


Natural Language Processing (NLP) is a subfield of Artificial Intelligence that enables computers to understand, interpret, and generate human language.


🔹 Goals of NLP

Understand human language (text/speech)
Extract meaning and intent
Generate human-like responses
Automate language-based tasks

🔹 Levels of NLP

Lexical Analysis
Deals with words and vocabulary
Example: identifying tokens
Syntactic Analysis (Parsing)
Checks grammar and sentence structure
Example: subject–verb relationships
Semantic Analysis
Extracts meaning from text
Example: understanding context
Pragmatic Analysis
Understands real-world intent
Example: sarcasm, implied meaning

🔹 NLP Pipeline (Step-by-Step)

Text Input
Preprocessing
Feature Extraction
Model Processing
Output (prediction/response)

🔹 Text Preprocessing Techniques


These are VERY IMPORTANT (used in almost every NLP task):

1. Tokenization

Splitting text into words/sentences
Example:
“I love AI” → [I, love, AI]

2. Stop Word Removal

Removing common words (is, the, and)

3. Stemming

Reducing words to root form
Example:
running → run

4. Lemmatization

More accurate root form using vocabulary
Example:
better → good

5. Lowercasing

Convert all text to lowercase


🔹 Feature Extraction (Text → Numbers)


Machines don’t understand text directly.

Techniques:
Bag of Words (BoW)
Counts word frequency
TF-IDF (Term Frequency – Inverse Document Frequency)
Weighs importance of words
Word Embeddings
Dense vector representation of words
Captures meaning and relationships

🔹 Important NLP Tasks

1. Text Classification
Spam detection
Sentiment analysis
2. Named Entity Recognition (NER)
Identifies names, places, dates
3. Machine Translation
Language conversion
4. Text Summarization
Shortens long text
5. Question Answering
Answers based on context
6. Speech Recognition
Converts speech → text

🔹 Traditional vs Modern NLP

Traditional NLP
Rule-based + statistical methods
Limited understanding
Modern NLP (Deep Learning)

Uses models like:

BERT
GPT

These are based on:

Neural Networks
Context understanding
Transformer architecture

🔹 What are Transformers?


A deep learning architecture that:

Processes entire sentences at once
Understands context better than older models

Key idea: Attention Mechanism
→ Focuses on important words in a sentence


🔹 Applications of NLP

Chatbots
Voice assistants
Google Translate
Email spam filters
Search engines

🔹 Challenges in NLP

Ambiguity (same word, different meanings)
Sarcasm & tone
Multiple languages
Context understanding

🔹 Popular NLP Libraries

NLTK → beginner-friendly
spaCy → fast & production-ready
Transformers (Hugging Face) → advanced models

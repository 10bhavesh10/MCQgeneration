# NLP-Powered Article Summarization and MCQ Generation


This project explores the application of natural language processing (NLP) techniques to automatically summarize articles and generate multiple-choice questions (MCQs) from the content.

# Key Features:
Text Preprocessing: Implemented various text cleaning and transformation methods, including HTML tag removal, punctuation removal, tokenization, stopword removal, stemming, and lemmatization.
Text Summarization: Utilized the BART transformer model to generate concise summaries of the input articles.
Keyword Extraction: Employed the KeyBERT library to identify the most relevant keywords from the article summaries.
MCQ Generation: Developed a custom MCQgenerator class to create multiple-choice questions based on the extracted keywords. The questions include a masked keyword, the correct answer, and distractors generated using WordNet relationships.
Gradio UI: Designed a Gradio-based user interface to make the application accessible and user-friendly. The UI allows users to input articles, view the generated summaries, keywords, and MCQs, and interact with the various functionalities.


# Usage

Ensure you have the required dependencies installed, which can be found in the requirements.txt file.
Run the main.py script to start the Gradio UI application.
In the web interface, users can enter the text of an article and click the "Generate" button to see the summarized text, extracted keywords, and multiple-choice questions.
The UI provides a clean and intuitive layout, allowing users to easily navigate and interact with the NLP-powered features.

# Future Enhancements

Expand the article dataset and evaluate the performance of the NLP models on a larger scale.
Integrate the MCQ generation functionality into an interactive educational platform or assessment tool.
Explore more advanced techniques for distractor generation, such as leveraging language models or contextual information.
Enhance the Gradio UI with additional features, such as the ability to save and load article data, export generated content, and provide more customization options.

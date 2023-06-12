# A-simple-Chatbot-using-NLP
The necessary imports are done, including PyPDF2, nltk, and the required modules for tokenization and language processing.

The Google Drive is mounted to access the PDF file.

The PDF file is loaded and its content is extracted as text using PyPDF2.

NLP-related packages and resources are downloaded using nltk's download function.

The extracted text is preprocessed by replacing newline characters and tokenizing the text into sentences and words.

A list of questions is defined.

An empty list called "answers" is initialized to store the answers for each question.

For each question, the chatbot searches for keywords in the extracted sentences and finds the first sentence that matches the keywords.

If a matching sentence is found, it is added to the answers list. Otherwise, a default "Sorry" message is added.

Finally, the answers are displayed.

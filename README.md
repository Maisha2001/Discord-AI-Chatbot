# Discord-AI-Chatbot

An AI based chatbot that learns the patterns of all new sentences and associates them with the tags to get responses from a JSON file. The AI model was built and trained using Natural Language Processing (NLP). TensorFlow and NLTK was used for the construction of the model. 

</p>
When the user writes a sentence and sends it to the chatbot, the model follows 3 basic steps:
<ol>
<li>Sentence segmentation: This step consists of dividing the written text into meaningful units.</li>
<li>Word tokenization: The units from the first step serve as input for this step, where they are divided into smaller parts called “tokens”. These tokens are very  useful for finding such patterns.</li>
<li>Text Lemmatization: In this step, a lexical treatment is applied to the text in order to analyze it. Then, the model predicts tag of the sentence so it can choose a proper response.</li>
</ol>
</p>

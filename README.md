# Dimensionless_Technologies<br />

PROBLEM STATEMENT: We have to analyze the audio file present and extract the Intent and Entities from that.<br />

Solution Apprach:<br />
Step1: Use Wav2Vec to convert the Audio to the text format.<br />
Step2: In the Data set we have two kinds of Intents ie: 'Intro' and 'Purpose'. So this task can be modelled as a **Binary Text classification task using LSTM.**<br />
Step3: We modelled a LSTM network using **Keras** for training purpose with two classes as 'Intro' and 'Purpose' and could achive an accuracy of 98%. <br />
Step4: The next task was to recognize the entities. We modelled this as the **Named Entity Recognition** task. <br />
Step5: We used the **Named Entity Recognition model from Spacy** to train this and find out the entities as the "caller name", "company name" and "product name".<br />

To execute the applciation.<br />
There is no additional dependencies to execute this. We can just download the .ipynb file and run it.

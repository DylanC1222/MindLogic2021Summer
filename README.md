# My Main Project as a Software Engineer Intern at Mindlogic

### The step-by-step plan behind my team's machine learning project at the company
1. Gather roughly 50000 back-and-forth messages from a diverse set of American English-speaking users on Facebook's Messenger app using Mindlogic's conversation AI
2. Group the gathered messsages into meaningful and distinct groups with roughly the same intent with as little overlap between each group as possible
3. Create a machine learning model to classify the grouped messages into a predefined grammar structure of positive/negative, tense, form, subject, and primary intent

### How me and my team accomplished each step of the machine learning project
1. Created a Django-based Facebook Messenger chatbot hosted on Mindlogic servers (Led by my partner Jeeyoo Kim from Berkeley CS)
2. Used KMeans to group responses interpreted by Google's Universal Sentence Encoder to group similar responses together (Led by me)
The code is presented in kmeansCluster.ipynb
3. Used Hugging Face's Transformers to create two PyTorch models based on Distilbert and Electra Small (Led by me)
The code is presented in distilbertElectraModel.ipynb
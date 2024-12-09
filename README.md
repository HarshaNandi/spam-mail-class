<h1>Introduction of spam mail classification</h1>
<p>Introduction:In today's digital era, email communication plays a vital role in both personal and professional domains. However, the increasing volume of spam emails has become a significant challenge, leading to wasted time, reduced productivity, and potential security risks such as phishing and malware attacks. 

Objective:1)	Accurate Classification: Develop a model that can accurately classify emails with high precision and recall.
2)	Real-time Processing: Design a system that can process incoming emails in real-time to enable immediate filtering and categorization.
3)	Scalability: To handle large volumes of incoming emails efficiently.
1.4	Scope of the Project: 
Scope: 
1)	Automated Email Classification: The system can automatically classify emails as spam or not spam based on content, metadata.
.
2)	Real-time Spam Detection: The model can process incoming emails in real time, allowing users to receive only legitimate emails in their inbox.

3)	Adaptability: Models can be trained to adapt to new types of spam by continuously learning from new data.

4)	Feature Extraction: NLP techniques can extract meaningful features from email content.

</p>

<h2>Description of the project</h2>
<P>Step1: I import the necessary libraies for the code
   Step2: Putting the csv file and read it 
   Step3: Taking the data of csv file and decleared the spam and ham as 0 and 1
   Step4: Check for any null value
   Step5: I take 2 new variable x and y where i store the value of massage and category
   Step6: Take the countventorizer to fit
   Step7:I split the data set in train and test case
   Step8: Fit the model for NLP
   Step9: Ckecking the model accuracy score with model.predict which is 98.48%
   Step10: Now i train the model
   Step11: I check for the model score for both train and test case
   Step12: In this step , I completed several actions like - Input email/message to classify,Data must be in a list to be compatible with vectorizer,Convert text to numerical features using CountVectorizer,Predict whether the message is spam (1) or not spam (0)
   Step13: Imports the Pickle module, which is used to serialize and deserialize Python objects.
   Step14: It saves the CountVectorizer so one can reuse it later for transforming new, unseen data.</P>
   <p>In another python file I import the streamlit and pickle to make an UI interface for our website.I added title, text and custom button to classify the mail.</p>
   <h3>Output</h3>
   <p>Firstly , I opened the terminal then write a command- streamlit run "c:\Users\HARSHA NANDI\OneDrive\Desktop\spam mail class\spamdetector.py". Then a webinterface will come which i made to classify the mail</p>

# PROJECT OVERVIEW

## C. PROJECT IMPLEMENTATION
### Deliverables:
Hardware Requirement :
For this project, the hardware that is being used is an ASUS TUF Gaming Laptop which consists of AMD Ryzen 5 and 16GB of RAM to run the training model.

### Software Requirement :
In software case, we utilize python programming language to implement both the code for intelligent module in detecting fake news and to design the web application.


### Intelligent System Architecture:
The proposed technique is Passive Aggressive Classifier, which is a type of machine learning technique.<br>
Passive Aggressive Classifier Architecture:<br>
<img src="/assets/PAC diag.png" width = 50%>

#### Outcomes of the system
2 main steps will be applied in our system, which is text pre-processing and fake news detection. Given a dataset of news articles, the first step is to generate TF-IDF which refers to Term Frequency-Inverse Document Frequency to see the importance of each word to a corpus and removing stopwords so that we will only see high-level information words in the TF-IDF. The processed data is the splitted into training and testing data, and were fit into Passive Aggressive Classifier for fake news detection.<br>
<img src="/assets/Implementation.png" width = 60%>






























**Next:** [Project Execution](/Project-Management-Plan/D-Project-Execution.md)

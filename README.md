<!-- PROJECT TITLE -->
<h1 align="center">Movie Reviews Sentiment Analysis</h1>

<!-- HEADER -->
<p align="center">
  <img src="Images/Movies_Header.jpg"/>
</p>

<!-- PROJECT DESCRIPTION -->
## <br>**➲ Project description**
Movie reviews sentiment analysis is a project which is based on natural language processing, where we use NLP techniques to extract useful words of each review and based on these words we can use binary classification to predict the movie sentiment if it's positive or negative

<!-- PREREQUISTIES -->
## <br>**➲ Prerequisites**
This is list of required packages and modules for the project to be installed :
* <a href="https://www.python.org/downloads/" target="_blank">Python 3.x</a>
* Pandas 
* Numpy
* re
* Scikit-learn
* NLTK

Install all required packages :
 ```sh
  pip install -r requirements.txt
  ```
<!-- THE DATASET -->
## <br>**➲ The Dataset**
Human activites dataset contain about 50000 record which is a sample of movie's review<br>
and a target column "sentiment" which describe the sentiment of the viewer about the movie either it is positove or negative<br>
<br>**Dataset features and target :**<br>
![](Images/Dataset_Columns.png)<br>
<br>**Dataset head :**<br>
![](Images/Dataset_Head.png)

<!-- CODING SECTIONS -->
## <br>**➲ Coding Sections**
In this part we will see the project code divided to sections as follows:
<br>

- Section 1 | Data Preprocessing :<br>
In this section we aim to do some operations on the dataset before training the model on it,
<br>processes like :
  - Loading the dataset
  - Encoding ouput to binary (Positive : 1 , Negative : 0) 
  - Data cleaning : Remove HTML tags
  - Data cleaning : Remove special characters
  - Data cleaning : Convert everything to lowercase
  - Data cleaning : Remove stopwords
  - Data cleaning : Stemming<br><br>

- Section 2 | Model Creation :<br>
The dataset is ready for training, so we create a Naive Bayes model using scikit-learn and then fit it to the data.<br>

- Section 3 | Model Evaluation :<br>
Finally we evaluate the model by getting accuracy, classification report and confusion matrix.

<!-- INSTALLATION -->
## <br>**➲ Installation**
1. Clone the repo
   ```sh
   git clone https://github.com/omaarelsherif/Movie-Reviews-Sentiment-Analysis-Using-Machine-Learning.git
   ```
2. Run the code from cmd
   ```sh
   python movie_reviews_sentiment_analysis.py
   ```

<!-- OUTPUT -->
## <br>**➲ Output**
Now let's see the project output after running the code :

**Dataset head :**<br>
![](/Images/Output_1_Dataset_Head.png)<br><br>

**Dataset after output encoding :**<br>
![](/Images/Output_2_Dataset_After_Encoding.png)<br><br>

**Review sample after removing HTML tags :**<br>
![](/Images/Output_3_Review_After_Remove_HTML.png)<br><br>

**Review sample after removing special characters :**<br>
![](/Images/Output_4_Review_After_Remove_Special_Chars.png)<br><br>

**Review sample after converting words to lowercase :**<br>
![](/Images/Output_5_Review_After_Converting_To_Lowercase.png)<br><br>

**Review sample after removing stopwords :**<br>
![](/Images/Output_6_Review_After_Remove_Stopwords.png)<br><br>

**Review sample after stemming words :**<br>
![](/Images/Output_7_Review_After_Stemming_Words.png)<br><br>

**Bag Of Words "BOW" :**<br>
![](/Images/Output_8_BOW.png)<br><br>

**Models accuracy :**<br>
![](/Images/Output_9_Models_Accuracy.png)<br>

<!-- REFERENCES -->
## <br>**➲ References**
These links may help you to better understanding of the project idea and techniques used :
1. Natural Language Processing (NLP) : https://ibm.co/38bN03T
2. Sentiment analysis : https://bit.ly/3yi9BGq
3. Naive Bayes classifier : https://bit.ly/3zhoWIO
4. Model evaluation : https://bit.ly/3B12VOO

<!-- CONTACT -->
## <br>**➲ Contact**
- E-mail   : [omaarelsherif@gmail.com](mailto:omaarelsherif@gmail.com)
- LinkedIn : https://www.linkedin.com/in/omaarelsherif/
- Facebook : https://www.facebook.com/omaarelshereif

WEB SCRAPPING USING PYTHON SENTIMENT ANALYSIS


![image](https://github.com/Savitha2512/python-2/assets/137802187/4f2fa038-e0d2-4cda-8c76-d6419c855bdd)

 
Import libraries


 ![image](https://github.com/Savitha2512/python-2/assets/137802187/87906510-18e4-4b37-91f9-7e61d0a3f620)




DATA OBTAINED FROM WIKIPEDIA


![image](https://github.com/Savitha2512/python-2/assets/137802187/85084f4c-1710-4350-80d4-2bc832677b12)

 


Firstly we have to clear the content. For that we have to import regular expression library
We will have to clear the content by giving these codes


 ![image](https://github.com/Savitha2512/python-2/assets/137802187/b6fd1f93-ac8b-4dce-9589-ad923131de6a)

After this codes will appear without special characters.
IMPORTING BEAUTIFUL SOUP:

To scrape the data beautiful soup should be imported and through requests we must get the http address.

![image](https://github.com/Savitha2512/python-2/assets/137802187/5368ba7b-e747-4d8e-9795-3d7e481bf1bc)
 

IMPORT NLTK FOR TOKENIZE

![image](https://github.com/Savitha2512/python-2/assets/137802187/b7754535-4f7d-46aa-940f-898a0a958c8e)

 
Sent_tokenize will help in fine tuning of sentence. Using this function the wikepedia content was tuned and sentence came out without special characters and in a more presentable manner.
ANALYSIS


 ![image](https://github.com/Savitha2512/python-2/assets/137802187/4430ba10-dd85-492a-be9a-0cc2865d2b15)

With the if loop neutral, positive and negative sentiment in the Wikipedia content was analysed

FREQUENTLY DISTRIBUTED WORDS


Frequently occurring words from wikepedia content are plotted as a graph.


 ![image](https://github.com/Savitha2512/python-2/assets/137802187/9a842372-ac77-455e-b8fa-5db619bd2b7f)


 
Wordcloud


![image](https://github.com/Savitha2512/python-2/assets/137802187/13e5a9d1-c3ae-42b9-bf23-57e814bd4329)
 
Wordcloud was built with the content of the Wikipedia and repeated words.

 
![image](https://github.com/Savitha2512/python-2/assets/137802187/713ac260-615b-4187-bea7-0c072e1a18b1)

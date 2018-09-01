# Doc_Searcher

### src : 
source code for project

### Wiki_Data : 
Training data scraped off wikipedia . Consists of approx 3500 docs each having more than 180 words each . The training test consists of three totally seperate documents of 'Country' ,'Dog species' and 'English football stadiums'

### models : 
The 2 trained models 

### test_docs : 
5 test documents , of topics 'History of India' ,  'Dog' , 'Edgbaston Cricket Ground' , 'Scooby-Doo (character)','Eden Gardens' . The script to find top 10 similar docs can be found in src/similarity_finder.ipynb

# ABOUT src

### Wiki_API
Wikipedia scrapper , making use of Wikipedia API to extract data heading by heading off relevant pages . If content is less than 180 words , no document is made. This way headings such as References and others do not train the model.

### model_trainer
model training using gensim doc2vec .

### test_doc_maker
script used to make test_doc

### similarity_finder
script to find and display top 10 matching docs to test_docs. 

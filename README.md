# Named-Entity-Recognition
Data provided by Mondaq limited was 500 legal articles for named entity recognition.It was  unstructures data. BRAT annotation tool was used to create training dataset. 
Data scanning was done by annotating the data with sPacy and comparing the output with BRAT annotation. Once the training data was ready with labels the brat annotated data which was in standoff format was converted to csv format with tokenization and POS tagging.

STANFORD NER method
It is a java based open source for NER. Feature factory was analysed and suitable features were selected and property file was generated to check on the accuracy.

Conditional Random Field
CRF is a supervised learning algorithm. Feature extraction was performed by analysying the articles provided as in NER features are domain specific.

spaCy
spaCy is a open source aplication. NER pipelne was chosen and analysis was performed. Data is converted from tsv to json and from json to spacy acceptable format.

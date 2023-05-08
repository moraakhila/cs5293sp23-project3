# cs5293sp23-project3
# The Smart City Slicker

The term “smart city” is widely used, but there is no consensus on the definition. Many citizens and stakeholders are unsure about what a smart city means in their community and how it affects them. Imagine you are a stakeholder in a rising Smart City and want to know more about themes and concepts about existing smart cities. You also want to know where does your smart city place among others. In this project, you will use text analysis techniques to investigate themes and similarities for smart cities with the use of cluster analysis, topic modeling, and summarization. This project can help you as a stakeholder understand smart cities using data from the 2015 Smart City Challenge.

Author Details
* Name: Akhila Mora
* Email: akhila.mora@ou.edu
* Student ID: 113531532

# Getting Started
Below are the starting steps which needs to be done before starting the project:
* In Ubuntu, connect to the VM instance using the following command:
```
ssh -i [path-to-private-key] [username]@[instance-external-ip]
```
* We need to have python installed in the instance. If not, install it using below command:
```
sudo apt-get install python3
```

# Packages
Following are some of the packages used for this project: 
* pypdf
* pandas
* os
* nltk
* spacy
* re
* en_core_web_md
* sklearn

# Executing program
Below is the detailed explanation on how to run the project:
* Clone the project into your instance:
```
git clone https://github.com/moraakhila/cs5293sp23-project3
```
* Change the current working directory to cloned repository:
```
cd cs5293sp23-project3
```
* Create a virtual environment
```
pipenv install
```
* Activate virtual environment
```
pipenv shell
```
* Install necessary packages
```
  pipenv install nltk
  pipenv install pytest
  pipenv install sklearn
  pipenv install pandas
``` 

## Acknowledgments
* [Github Readme template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
* [Model Persistence](https://scikit-learn.org/stable/model_persistence.html)
* [Contractions](https://github.com/dipanjanS/text-analytics-with-python/blob/master/New-Second-Edition/Ch05%20-%20Text%20Classification/contractions.py)
* [Text normalization](https://github.com/dipanjanS/text-analytics-with-python/blob/master/New-Second-Edition/Ch05%20-%20Text%20Classification/text_normalizer.py)

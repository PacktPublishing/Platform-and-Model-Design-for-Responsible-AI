# Platform and Model Design for Responsible AI

<a href="https://www.packtpub.com/product/platform-and-model-design-for-responsible-ai/9781803237077?utm_source=github&utm_medium=repository&utm_campaign=9781803237077"><img src="https://content.packt.com/B18681/cover_image_small.jpg" alt="Platform and Model Design for Responsible AI" height="256px" align="right"></a>

This is the code repository for [Platform and Model Design for Responsible AI](https://www.packtpub.com/product/platform-and-model-design-for-responsible-ai/9781803237077?utm_source=github&utm_medium=repository&utm_campaign=9781803237077), published by Packt.

**Design and build resilient, private, fair, and transparent machine learning models**

## What is this book about?
AI algorithms are ubiquitous and used for tasks, from recruiting to deciding who will get a loan. With such widespread use of AI in the decision-making process, it’s necessary to build an explainable, responsible, transparent, and trustworthy AI-enabled system. With Platform and Model Design for Responsible AI, you’ll be able to make existing black box models transparent.

This book covers the following exciting features: 
* Understand the threats and risks involved in ML models
* Discover varying levels of risk mitigation strategies and risk tiering tools
* Apply traditional and deep learning optimization techniques efficiently
* Build auditable and interpretable ML models and feature stores
* Understand the concept of uncertainty and explore model explainability tools
* Develop models for different clouds including AWS, Azure, and GCP
* Explore ML orchestration tools such as Kubeflow and Vertex AI
* Incorporate privacy and fairness in ML models from design to deployment

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/B09NC5XJ6D) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
model.compile(optimizer='rmsprop', loss=aleatoric_loss, metrics=['mae'])
```


**Following is what you need for this book:**
This book is for experienced machine learning professionals looking to understand the risks and leakages of ML models and frameworks, and learn to develop and use reusable components to reduce effort and cost in setting up and maintaining the AI ecosystem.		 

With the following software and hardware list you can run all code files present in the book (Chapter 1-14).

### Software and Hardware List

Each chapter has different requirements, which have been specified in their respective chapters.
You should have basic knowledge of ML, Python, scikit-learn, PyTorch, and TensorFlow to better
understand the concepts of this book.


### Related products <Other books you may enjoy>
* Network Science with Python [[Packt]](https://www.packtpub.com/product/network-science-with-python/9781801073691) [[Amazon]](https://www.amazon.com/dp/1801073694)

* Graph Data Science with Neo4j [[Packt]](https://www.packtpub.com/product/graph-data-science-with-neo4j/9781804612743) [[Amazon]](https://www.amazon.com/dp/B0BT1TQHPC)

## Get to Know the Authors
**Amita Kapoor**
is an accomplished AI consultant and educator, with over 25 years of experience. She
has received international recognition for her work, including the DAAD fellowship and the Intel
Developer Mesh AI Innovator Award. She is a highly respected scholar in her field, with over 100
research papers and several best-selling books on deep learning and AI. After teaching for 25 years
at the University of Delhi, Amita took early retirement and turned her focus to democratizing AI
education. She currently serves as a member of the Board of Directors for the non-profit Neuromatch
Academy, fostering greater accessibility to knowledge and resources in the field. Following her
retirement, Amita also founded NePeur, a company that provides data analytics and AI consultancy
services. In addition, she shares her expertise with a global audience by teaching online classes on
data science and AI at the University of Oxford.

**Sharmistha Chatterjee**
is an evangelist in the field of machine learning (ML) and cloud applications,
currently working in the BFSI industry at the Commonwealth Bank of Australia in the data and
analytics space. She has worked in Fortune 500 companies, as well as in early-stage start-ups. She
became an advocate for responsible AI during her tenure at Publicis Sapient, where she led the digital
transformation of clients across industry verticals. She is an international speaker at various tech
conferences and a 2X Google Developer Expert in ML and Google Cloud. She has won multiple awards
and has been listed in 40 under 40 data scientists by Analytics India Magazine (AIM) and 21 tech
trailblazers in 2021 by Google. She has been involved in responsible AI initiatives led by Nasscom
and as part of their DeepTech Club.




# Additional Information

### Chapter 1
*	keras-2.7.0, Tensorflow-2.7.0
*	pip install adversarial-robustness-toolbox
*	pip install git+https://github.com/Koukyosyumei/AIJack

Reference :https://github.com/Koukyosyumei/AIJack/tree/main/src/aijack,
https://github.com/Trusted-AI/adversarial-robustness-toolbox

### Chapter 2

* pip install adversarial-robustness-toolbox
*	pip install presidio_analyzer
*	pip install presidio_anonymizer
*	pip install syft==0.2.9
*	pip install Pyfhel
*	pip install secml
*	pip install crypten
*	git clone https://github.com/privacytrustlab/ml_privacy_meter.git , pip install -r requirements.txt, pip install -e
*	pip install diffprivlib
*	pip install tensorflow-privacy
*	pip install mia
*	pip install foolbox

### References :
* https://github.com/OpenMined/PySyft
* https://github.com/ibarrond/Pyfhel
* https://github.com/pralab/secml
* https://github.com/facebookresearch/CrypTen
* https://github.com/IBM/differential-privacy-library
* https://github.com/tensorflow/privacy
* https://github.com/bethgelab/foolbox
* https://github.com/privacytrustlab/ml_privacy_meter.git 




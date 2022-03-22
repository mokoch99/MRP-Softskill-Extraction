# A Context-aware fine-grained skill extraction system using Natural Language Processing
### A. Gade, A. Jaishankar, M. Koch, K. Kramer, S.M. Tazwar, V. Tzatziou

The HR recruitment process for vacant positions has grown more challenging, in part due to the increased amount of job applications needing processing. With older systems using basic boolean information retrieval processes, a newer, context-based, approach could accommodate the need for a more skill- and experience-based hiring process that not only puts focus on hard skills but also soft skills. Such a system cannot only extract hard and soft skills, but also their domains and sub-domains would improve effectiveness and reduce costs in an already long hiring process. This project proposes such a context-based and fine-grained classification approach. State-of-the-art word embeddings are used as linguistic features for a set of classical and state-of-the-art machine learning classifiers. These models are trained and validated on a public job-advertisement dataset, which has been labeled using a taxonomy consisting of 1975 of the most common skills found in job advertisements. Results of our evaluations show, that a random classifier using custom FastText embeddings outperforms a BI-LSTM. The results for predicting a small set of unknown skills with the models show that they are robust, to a certain degree. This project also includes the development of a web application (https://skillum.de), that allows the user to interact with the models developed in this project online.   


As this repositry contains large data files, please be advised that git lfs is required to clone this repository!


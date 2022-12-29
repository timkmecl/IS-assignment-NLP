### Second assignment for **Intelligent Systems** course, UL FRI 2021/22
- *Lecturer:* prof. dr. Marko Robnik Šikonja
- *Assistants:* Blaž Škrlj, Tadej Škvorc

*The assignment was done in collaboration with Bernard Sovdat. Data was provided by the staff.*

# **Natural language processing** in Python

We had to use machine learning algorithms on labeled text documents to detect fake news. In addition to assignment requirements, we used BERT implementation in PyTorch to generate text embeddings and used them as features for classification.

- [instructions](instructions.pdf)
- [code](is2.ipynb)
- [report](report.pdf)


### Summary:
The seminar assignment involves working with sequential data, specifically labeled text documents, to detecting fake news. 

The task is to pre-process the documents, construct features, model the documents, and evaluate the results. 
- Pre-processing includes cleaning the documents of noise and computing basic statistics. 
- Feature construction involves converting the documents into a real-valued matrix suitable for learning, and discussing the choices made and the final space used. 
- Modeling involves using at least three machine learning classifiers and one ensemble method to train on the training data and produce predictions for the test data. 
- Evaluation involves implementing classification accuracy and F1 score, comparing the performance to baselines, and placing the best solution within the context of the provided baselines.
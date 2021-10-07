# LeQua: Learning to Quantify

The aim of LeQua 2022 is to allow the comparative evaluation of methods for ”*learning to quantify*” in textual datasets, i.e., methods for training predictors of the relative frequencies of the classes of interest in sets of unlabelled textual documents. These predictors (called “*quantifiers*”) will be required to issue predictions for several such sets, some of them characterized by class frequencies radically different from the ones of the training set.

- **Task A**: This task is concerned with evaluating *binary quantifiers*, i.e., quantifiers that must only predict the relative frequencies of a class and its complement. Participants in this task will be provided with training and test documents already converted in *vector form*; the task is thus suitable for participants who do not wish to engage in generating suitable representations for the textual documents, but want instead to concentrate on optimizing the methods for learning to quantify.
  
- **Task B**: This task is concerned with evaluating *single-label multi-class quantifiers*, i.e., quantifiers that operate on documents that each belong to exactly one among a set of n>2 classes. Like in Task A, participants will be provided with training and test documents already converted in *vector form*.
  
- **Task C**: Like Task A, this task is concerned with evaluating *binary quantifiers*. Unlike in Task A, participants will be provided with the *raw text* of both training and test documents; the task is thus suitable for participants who also wish to engage in generating suitable representations for the textual documents, or to train end-to-end systems.
  
- **Task D**: Like Task B, this task is concerned with evaluating *single-label multi-class quantifiers*; like in Task C, participants will be provided with the *raw text* of both training and test documents.
    
    
    

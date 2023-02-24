# hulat_edos
This repository contains the code for our participation at SemEval 2023 - Task 10 - Explainable Detection of Online Sexism (EDOS)
 (https://codalab.lisn.upsaclay.fr/competitions/7124)


* 1_data.ipynb: in this notebook, you can find code to study the dataset of the task. For example, you will find some plots about the distribution of the classes in the three tasks. We also create plots for the length of the texts.
* 2_system.ipynb: this notebook allows you to reproduce all our experiments by using the training and test dataset provided by the organizers of the task. To obtain the file edos_labelled.csv, you must contact with the organizers.
* 3_DA4edos.ipynb: this notebook includes the data augmentation techniques that we used to increase the training dataset for this task.


A detailed description of our system is described in:

    @InProceedings{segura2023hulatintimacy,

    title={HULAT at SemEval-2023 Task 10: Data augmentation for pre-trained transformers applied to the detection of sexism in social media},

    author={Segura-Bedmar, Isabel},

    booktitle = {17th International Workshop on Semantic Evaluation (SemEval-2023)},

    year = {2023}

    }

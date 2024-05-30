# Introduction
A skin lesion is defined as a superficial growth or patch of the skin that is visually different and/or has a different texture than its surrounding area. Skin lesions, such as moles or birthmarks, can degenerate and become cancer, with melanoma being the deadliest skin cancer. Its incidence has increased during the last decades, especially in the areas mostly populated by white people.

The most effective treatment is an early detection followed by surgical excision. This is why several approaches for skin cancer detection have been proposed in the last years (non-invasive computer-aided diagnosis (CAD) ).

# Data
You will use a data-set of 25331 dermoscopic images of skin lesions with, when available, their relative segmentation and metadata (age, sex and anatomical position). Data has already been randomly split into a training-validation set (75%) and a test set (25%). You only have the classification (made by clinicians) of the training-validation set. The goal of the project is to estimate the correct class of each dermoscopic image in the test set. **You can only use the data provided in this challenge**

# Feature extraction
You can use all features you'd like. A list of references describing very well-known features can be found at the end of this page but you can find many more articles in the Literature. You can use Pubmed, Google Scholar or simply Google to look for them. By using the network of Télécom Paris or its VPN , you will have automatically access to most of the scientific journals. If you have any trouble, do not hesitate to contact me, pietro.gori@telecom-paris.fr.

# Evaluation
The evaluation of the challenge will be based on 1) the ranking in the leaderboard (both private and public), 2) a report and 3) the quality of your code.

The student, who will have the best ranking in the (private) leaderboard at the end of the challenge, will have between 2 and 4 points more in the final grade (depending on the result).

You will have to write a report where you will thoroughly explain the extraction of the features, the classification algorithms you used, why you chose them and the potential pre- and post-processing. You will have to explain the results saying if and why you expected those results. Be careful ! You will be penalised if you simply do a list of results like "I tried this algorithm but it did not work so I tried another one and so forth …" !!

Write a proper, commented and clean code in Python 3. I will test it and if it does not work you will have a penalty on the grade. Please write at the beginning of your code the version of the libraries you used. You can write a set of functions with a main one - I will only run the main function - or a jupyter-notebook.

Everything, report and code, must be uploaded to E-campus in the section Challenge before the end of the challenge

# Methods
You must use Python 3 as programming language. I strongly suggest that you use numpy and scikit-learn.

You can use any pre-processing and post-processing - coded by you or correctly referenced in the report.

# References
- http://ieeexplore.ieee.org/document/918473/
- https://www.sciencedirect.com/science/article/pii/S0933365712001108#bib0180
- https://www.sciencedirect.com/science/article/pii/S0957417416302354#bib0023
- https://www.sciencedirect.com/science/article/pii/S0933365713001589
- https://www.nature.com/articles/nature21056
- https://hal-univ-bourgogne.archives-ouvertes.fr/hal-01250955/document
- https://workshop2021.isic-archive.com/
- https://workshop2020.isic-archive.com/#paper

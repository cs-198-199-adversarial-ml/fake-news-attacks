# fake-news-attacks

The [MODELS](https://drive.google.com/drive/folders/1wu55OdyG8O3zMsuGFmYSo4PaLrhUbKlF?usp=sharing) used in this study can be accessed through the link.

1. ```Attribution Scores``` - calculated attribution scores using integrated gradients for adverb removal and negate attacks.
2. ```Datasets``` - contains all the datasets used in this study. 
2a. Folders named ```Adv``` contains the adversarial datasets.
2b. Folders named ```Analysis``` contains the adversarial datasets with additional extracted features for further analysis.
2c. Folders named ```Vocab``` contains text files containing the vocabulary of test and train datasets for both the English and Filipino datasets.
2d. Folders named ```CleanFinal``` contains the cleaned and preprocessed datasets, specifically applied to the English dataset.
2e. Other files in the ```Datasets``` folder are the original datasets.
3. ```adverbs-removal```, ```paraphrase```, ```simple_negate``` are jupyter notebook files where we conducted and analyzed the adversarial attacks.
4. ```oov-rate``` is a jupyter notebook file that contains the process of calculating the OOV rate of the models.
5. ```ds_split``` is a jupyter notebook file that contains the process of preprocessing, splitting to test and train datasets, as well as training the models in this study.

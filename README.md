# IdHS
Indonesian HateSpeech Model

## Datasets

### Train&Val Dataset
The train and val datasets are sampled from [multi-label-hate-speech-and-abusive-language](https://github.com/okkyibrohim/id-multi-label-hate-speech-and-abusive-language-detection).
Train dataset has 10435 text and Val dataset has 2609 text.

### About This Data
Here we provide a data set for multi-label hate speech and offensive language detection on Twitter Indonesia. The main dataset can be seen in the re_dataset with label information as follows:

* **HS** : label words that encourage hatred;
* **Abusive** : derogatory language label;
* **HS_Individual** : hate speech aimed at individuals;
* **HS_Group** : speech that encourages hatred targeted at a group;
* **HS_Religion** : hate speech related to religion / belief;
* **HS_Race** : speech encouraging racial / ethnic hatred;
* **HS_ Physical** : words that encourage hatred related to physical / disability;
* **HS_Gender** : speech that encourages hatred regarding gender / sexual orientation;
* **HS_Gender** : hatred related to other slander / slander;
* **HS_Weak** : words that encourage hatred;
* **HS_Moderate** : hate speech;
* **HS_Strong** : words that encourage hatred.
For each label, '1' means yes (tweet includes that label), '0' mean no (tweet is not included in that label).


## Architecture

![alt text](https://github.com/aryawicaksana/idhs/blob/archi.jpg?raw=true)

## Accuracy & Loss

### Accuracy
![alt text](https://github.com/aryawicaksana/idhs/blob/acc.png?raw=true)

### Loss
![alt text](https://github.com/aryawicaksana/idhs/blob/loss.png?raw=true)


## Model

[model.h5](https://github.com/aryawicaksana/abusivetext_best_model.h5)

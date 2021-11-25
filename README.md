# Deap-dataset-analysis
An analysis conducted on the famous DEAP Dataset - a dataset for emotion analysis using psychophysiological measurements like EEG, EMG, ECG. 
The electroencephalogram (EEG) and peripheral physiological signals of 32 participants were recorded as each watched 40 one-minute long excerpts of music videos. Participants rated each video in terms of the levels of arousal, valence, like/dislike, dominance and familiarity. For 22 of the 32 participants, frontal face video was also recorded. A novel method for stimuli selection was used, utilising retrieval by affective tags from the last.fm website, video highlight detection and an online assessment tool.

![https://www.eecs.qmul.ac.uk/mmv/datasets/deap/img/brains.jpg](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/img/brains.jpg)
![https://www.eecs.qmul.ac.uk/mmv/datasets/deap/img/graph.png](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/img/graph.png)

Link to the original paper of the dataset: [https://www.eecs.qmul.ac.uk/mmv/datasets/deap/doc/tac_special_issue_2011.pdf](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/doc/tac_special_issue_2011.pdf)

In this colab is the code used to achieve >90 accuracy on the classification of the affective response of the participants. The model used was a Gradient Boosting Machine along with PCA decomposition.
# Confusion Matrix

![https://github.com/rmib200/Deap-dataset-analysis/blob/main/deap_cm.png](https://github.com/rmib200/Deap-dataset-analysis/blob/main/deap_cm.png)

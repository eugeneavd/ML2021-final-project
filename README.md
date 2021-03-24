# ML2021-final-project

## Modern approaches to the assessment of demand sensitivity based on upliftmodels and neural networks

Skoltech 2021 ML course

Authors: [Anastasia Smeshko](https://github.com/smeshk), Daria Ustinova, [Evgeny Avdotin](https://github.com/eugeneavd), Kundyz Onlabek

In modern business, a need for targeted offers often appears. One of the most common tasks is sending messages to customers who wouldn’t have purchased without this communication. Such problems need a specific approach that is uplift modeling. In this project, we consider the most popular uplift modeling techniques, such as the meta-learners and tree-based approaches. We compare several different classic machine learning models as well as neural networks for base models in meta-learners. Finally, we investigate the performance of the mentioned algorithms in different datasets, both real and synthesized.

### Installation
```
git clone https://github.com/eugeneavd/ML2021-final-project.git
cd ML2021-final-project
pip3 install -r requirements.txt
```

### Data

* [MineThatData E-Mail Analytics And Data MiningChallenge dataset by Kevin Hillstrom](https://blog.minethatdata.com/2008/05/best-answer-e-mail-analytics-challenge.html)
* Kuusisto synthetic dataset
* [X5 retail group dataset](https://ods.ai/competitions/x5-retailhero-uplift-modeling/data)

Data is available in [data](https://github.com/eugeneavd/ML2021-final-project/tree/main/data), but all download utilities are added to the notebooks

### Our approaches
* Metalearners
* Trees & random forests, boosting
* Neural Network

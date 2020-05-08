# Analyzing the Risk of Coronary Heart Disease with Discriminative Neural Networks
The application of data mining, machine learning and artificial intelligence techniques in the field of diagnos- tics is not a new concept, and these techniques have been very successfully applied in a variety of applications, especially in dermatology and cancer research. But, in the case of medical problems that involve tests resulting in true or false (binary classification), the data generally has a class imbalance with samples majorly belonging to one class (ex: a patient undergoes a regular test and the results are false). Such disparity in data causes prob- lems when trying to model predictive systems on the data. In critical applications like diagnostics, this class imbalance cannot be overlooked and must be given extra attention. In our research, we depict how we can handle this class imbalance through neural networks using a discriminative model and contrastive loss using a Siamese neural network structure. Such a model does not work on a probability-based approach to classify samples into labels. Instead it uses a distance-based approach to differentiate between samples classified under different labels.

Link to [paper](https://www.insticc.org/Primoris/Resources/PaperPdf.ashx?idPaper=91901), [Medium article](https://medium.com/@ayushkhaneja_69318/using-siamese-networks-with-unbalanced-data-c4a9658d5a15)


## About
The repository contains different Jupyter notebooks to highlight the change in parameters of accuracy and loss when different techniques are used on the data.

## Dataset
The dataset used is the Framingham Heart Study data with a high class imbalance between positive nd negative samples. It has a total of 4240 samples.

## Data Preparation
The data has many missing values which were imputed suitably based on data type. Also, the data underwent a thorough preprocessing before being fed into the network.

## Results
The discriminative model built using a Siamese network outperforms the base vanilla NN considerably.

## Citation

@inproceedings{2020khaneja,
  title={Analyzing the Risk of Coronaty Heart Disease with Discriminative Neural Networks},
  author={Khaneja, Ayush and Srivastava, Siddharth and  Rai,Astha and Cheema, A. S.  and  Srivastava, P. K.},
  booktitle={9th International Conference on Pattern Recognition Applications and Methods, INSTICC},
  year={2020}
}

# Capstone_Custom_NER_Classifiers
Custom NER Classifiers 


The Custom NER classifiers can be run with Java 1.8+ and Downloading the Stanford Core NLP classifiers and NER.

Setup needs to be done for environment variables in order to run the models.

The models are trained on tokens tagged using stanford NER Classifiers 3,4 and 7.

The features of individual classifiers are given below,

	ICON-NER1	ICON-NER2	ICON-NER3	ICON-NER4	ICON-NER5
Classifier Name	mehyog-csr-ner-model-icon.ser	infinity-csr-ner-model-icon.ser	dilafor-csr-ner-model-icon.ser	maps-csr-ner-model-icon.ser	twin-csr-ner-model-icon.ser
useClassFeature	TRUE	TRUE	TRUE	TRUE	TRUE
useWord	TRUE	TRUE	TRUE	TRUE	TRUE
useNgrams	TRUE	TRUE	TRUE	TRUE	TRUE
maxNgramLength	6	7	8	9	10
usePrev	TRUE	TRUE	TRUE	TRUE	TRUE
useNExt	TRUE	TRUE	TRUE	TRUE	TRUE

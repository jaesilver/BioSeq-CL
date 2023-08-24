# BioSeq-CL
RNA Sequence Classification (Coding and Non-Coding) using Machine Learning Algorithms
-------------------------------------------------------------------------------------


This repository contains the code and data for determining whether a given RNA sequence is a coding RNA or a non-coding RNA using machine learning algorithms. The project uses various features of the RNA sequence to train the models. 


# Features 
-  ORF length
	* T0
	* T1
	* T2
	* T3
-  ORF Ratio
-  Transcript Length
-  GC Content
-  Aromaticity
-  Isoelectric Point
-  Relative Codon Bias
-  Stop Codon Frequency
-  Molecular Weight
-  CpG Islands
-  Instability Index
-  Fickett Score
-  Gravy Score

# Dataset 

The data set used in this study consisted of both coding and long non-coding RNA sequences from the Homo Sapiens species. The coding RNA and  noncoding RNA sequences are downloaded from GENCODE  and NONCODE  databases. The sequences are in FASTA format and have been pre-processed to extract various features such as ORF length, protein coding potential, etc. The dataset is split into training and testing sets, with 80% of the data used for training and the remaining 20% used for testing.

# Models 

The following machine learning algorithms have been implemented for this project:

-    Logistic Regression
-    Support Vector Machine (SVM)
-    Naive Bayes
-    Random Forest

These models have been trained using the features extracted from the dataset and are used to predict whether a given RNA sequence is coding RNA or non-coding RNA.

# Requirements 

To run the code in this repository, you will need:

-    Python 3.x
-    NumPy
-    Pandas
-    Scikit-learn
-    Matplotlib

# Usage 

To run the code in the provided repository from source.


1. Clone the repository using the following command:

	```
	git clone https://github.com/jaesilver/BioSeq-CL.git
 	```

3. Install the required dependencies using the following command:

	```
 	pip install -r requirement.txt
	```


# Conclusion

This project shows that machine learning models can be used to accurately classify RNA sequences into coding or non-coding sequences based on various features. The models implemented in this project can be further optimized and used in various biological applications, such as identifying potential drug targets and understanding gene expression. So, let's go and explore the world of RNA with Machine Learning! 



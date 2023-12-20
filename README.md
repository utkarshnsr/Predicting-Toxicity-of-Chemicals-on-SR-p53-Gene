# Predicting-Toxicity-of-Chemicals-on-SR-p53-Gene


<ul>
<li>Used Tox21 Dataset (https://moleculenet.org/datasets-1) and machine learning algorithms (logistic regression, support vector machine, random forest classifier, and graph neural network) to classify toxicity of chemicals on SR-p53 gene</li>
  
<li>Achieved highest AUROC score of 0.81 using graph neural network</li>
</ul>


Cancer is one of the most common causes of death worldwide, second only to heart disease. One way cancer has been studied is through the impact that p53's function has on tumor growth. P53 is a protein family that is known to be a tumor suppressor gene, so studying the function of p53 is one way to gain insight into the likelihood that tumors will develop. Recently, scientists have been using machine learning as a way to learn more about biological problems and questions. This provides a cheaper and quicker alternative to other methods such as animal testing and clinical trials. To learn more about cancer and p53, we have developed two different approaches to classify chemicals that have been shown to have some impact on the function of p53. These approaches include non graph approach (logistic regression, support vector machines, random forest) and graph approach (graphical neural network). Chemical features were derived from Simplified Molecular Input Line-Entry
System (SMILES) sequences corresponding to the atoms and structure of each compound. The fraction of CSp3 hybridization, molecular weight, and number of hydrogen acceptors were the features selected to be used with the non graph approach models. Graph representation of SMILES strings were used for the graph approach model. Each non-graphical approach models have a decent AUROC score in the range from 0.75 to 0.79. The graphical approach has an AUROC score in the range from 0.75 to 0.81. Each of these scores is adequate for a machine learning model, however, ideally it would be higher.

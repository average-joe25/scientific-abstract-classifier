# scientific-abstract-classifier
Model trained on PUBMED RCT dataset to classify Scientific abstract into classes(Background,Objective, method, results, conclusion) for a easier read. <br>
Dataset : **PUBMED RCT 20K** <br>
Models Used : **BI-LSTM , BERT , CONV1D, DENSE, MULTI-INPUT(Text,character,relative positioning)** <br>
Best Model : **MULTI-INPUT(Text,character,relative positioning)** <br>
**accuracy : 85.856976938%**<br>**precision : 85.81582728%**<br> **recall : 85.856976938%**<br>**f1_score : 85.658800%**<br>
<h3>NOTE : Due to processing prower constraint reduced model4 is used for api deployment<br> accuracy~85% trainable params 1/5th of model4</h3>
## BEST PERFOMING MODEL
<img src="https://github.com/average-joe25/scientific-abstract-classifier/blob/main/Model-mutli_input.png">

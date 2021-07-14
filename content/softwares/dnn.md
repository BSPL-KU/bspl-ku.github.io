---
title: "DNN (Deep Neural Network)"

show_date: false 
reading_time: false # Show estimated reading time?
share: false # Show social sharing links?
profile: false # Show author profile?
comments: false # Show comments?
---

Deep neural network (DNN) with weight sparsity control (i.e., L1-norm regularization) improved the classification performance using whole-brain resting-state functional connectivity patterns of schizophrenia patient and healthy groups. Initializing DNN's weights through stacked auto-encoder enhanced the classification performance as well. (Kim et al., NI, 2016). Here, we provide MATLAB and Python based codes in terms of the DNN with the weight sparsity control 
([MATLAB code](http://bspl.korea.ac.kr/DNN_weightsparsity_MATLAB.zip) / [Python code](http://bspl.korea.ac.kr/DNN_weightsparsity_python.zip) download). 

**Reference**: Kim et al., Deep neural network with weight sparsity control and pre-training extracts hierarchical features and enhances classification performance: Evidence from whole-brain resting-state functional connectivity patterns of schizophrenia. NeuroImage. 2016 Jan.; 124(Pt A):127-46. 
[ [PubMed](http://www.ncbi.nlm.nih.gov/pubmed/?term=Deep+neural+network+with+weight+sparsity+control+and+pre-training+extracts+hierarchical+features+and+enhances+classification+performance%3A+Evidence+from+whole-brain+resting-state+functional+connectivity+patterns+of+schizophrenia) / 
[Google Scholar](https://scholar.google.co.kr/scholar?q=Kim+J%2C+Calhoun+VD%2C+Shim+E%2C+Lee+JH*%2C+Deep+neural+network+with+weight+sparsity+control+and+pre-training+extracts+hierarchical+features+and+enhances+classification+performance%3A+Evidence+from+whole-brain+resting-state+functional+connectivity+patterns+of+schizophrenia%2C+Neuroimage.+2016+Jan+1%3B124%28Pt+A%29%3A127-46.+doi%3A+10.1016%2Fj.neuroimage.2015.05.018.+Epub+2015+May+15.+&btnG=&hl=en&as_sdt=0%2C5) ]

#### MATLAB code ([download](http://bspl.korea.ac.kr/DNN_weightsparsity_MATLAB.zip))

Steps:
1. Download the MATLAB code as the above link
2. Open "test_WeightSparsity.m" file and prepare/load your own data
3. Divide your own data into training and test data set (i.e. 'train_x', 'train_y', 'test_x', 'test_y')
4. Determine how many hidden layers/nodes we are going to use
  > If you have two classes and want to use two hidden layers with 100 nodes, you can set as the following:
  >> \>> nn = nnsetup([784 100 100 2]);
5. Set the target weight sparsity levels at each layer (e.g. nn.nzr = [0.2 0.2]) and other parameters (e.g. learning rate, batch size etc.).
6. Run 'test_WeightSparsity.m'.
7. Make sure the convergence of the weight sparsity level to the target level for each hidden layer
  > The MATLAB codes were modified from the DeepLearnToolbox to apply non-zero ratio for weight sparsity control. 

#### Python code ([download](http://bspl.korea.ac.kr/DNN_weightsparsity_python.zip))

Steps:
1. Download the MNIST data from the link
2. Set parameters (e.g., learning rate, regularization term, etc.)in the "mlp_h3.py" code
3. Run the python code using "mlp_h3.py"
  > The Python codes were modified from the DeepLearningTutorials to apply non-zero ratio for weight sparsity control.

For any questions or comments, please contact Jong-Hwan Lee (jonghwan_lee@korea.ac.kr), Hyun-Chul Kim (hyunchul_kim@korea.ac.kr) or Hojin Jang (hojin4671@gmail.com).

Please also check out our [github](https://github.com/bsplku/dnnwsp)!


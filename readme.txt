Q1.

There are 4 notebooks, which represent the 4 models we tried out
1. q1_linear.ipynb -> contains the code for just 1 linear layer + softmax 
2. q1_bilsm_layer -> contains the code for bilstm + linear layer + softmax
3. q1_cnn_bilstm -> contains code for cnn+ bilstm + softmax
4. q1_cnn_bilstm_crf_final -> contains code for cnn + bilstm + crf 

There is one model saved: best_model_cnn.crf.pth, you can load this model in the q1_cnn_bilstm_crf_final
Run all the cells till the training script and run the last cell for the evaluation.

The code is pretty much simple, and there are some comments at the important junctures. 
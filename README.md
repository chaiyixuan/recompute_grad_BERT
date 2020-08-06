# recompute_grad_BERT
Useing tf.recompute_grad() for BERT to extend the batch_size*3
Just work at tensorflow==1.15.0

使用在BERT上使用重计算来节约显存（大概batch_size可以增大3倍），只在tf 1.15.0版本上测试有用。





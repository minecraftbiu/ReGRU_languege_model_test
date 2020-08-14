# ReGRU_languege_model_test

This source code is part of the source code for testing and does not contain the improved source code involved in this article.

PTB dataset from Tomas Mikolov's webpage is in the input directory, download :
wget http://www.fit.vutbr.cz/~imikolov/rnnlm/simple-examples.tgz 
tar 
(Download address source: https://github.com/tensorflow/models/blob/r1.4.0/tutorials/rnn/ptb/ptb_word_lm.py)

ptb_regru_layer3_epoch40 contains model.pt and result.md with 40 Epoch of 3 layers of ReGRU
Download link:
https://www.dropbox.com/sh/u5kelujf9akll5v/AACKS0V69IHiZcntxP0hXmCoa?dl=0

ptb_regru_layer7_epoch40 contains model.pt and result.md with 40 Epoch of 7-layer ReGRU
Download link:
https://www.dropbox.com/sh/xh9qa8j7o0d73pu/AAACglSQPwjW5KDd648Ut4fxa?dl=0

model.pt is a model file trained based on the PTB data set.
result.md is the log record of training and testing.


How to use the test code:
Move the model.pt model file in the ptb_regru_layer3_epoch40 or ptb_regru_layer7_epoch40 folder to the root directory.
Execute test.py to get the test result.

On the PTB data set, the ppl value obtained by this model reaches 23.81

This code is a change of the official source code of pytorch:
https://github.com/pytorch/examples/tree/master/word_language_model

------------------------------------------------


本源码为测试部分源码，不包含本文所涉及的改进源码。

input目录下为Tomas Mikolov的链接，下载方式：
wget http://www.fit.vutbr.cz/~imikolov/rnnlm/simple-examples.tgz 
（下载地址来源：https://github.com/tensorflow/models/blob/r1.4.0/tutorials/rnn/ptb/ptb_word_lm.py）

ptb_regru_layer3_epoch40中包含3层ReGRU迭代40次的model.pt和result.md
下载链接：
https://www.dropbox.com/sh/u5kelujf9akll5v/AACKS0V69IHiZcntxP0hXmCoa?dl=0

ptb_regru_layer7_epoch40中包含7层ReGRU迭代40次的model.pt和result.md
下载链接：
https://www.dropbox.com/sh/xh9qa8j7o0d73pu/AAACglSQPwjW5KDd648Ut4fxa?dl=0

model.pt是根据PTB数据集训练好的模型文件。
result.md是训练和测试的日志记录。

测试代码使用方法：
将ptb_regru_layer3_epoch40或ptb_regru_layer7_epoch40文件夹的model.pt模型文件挪至根目录。
执行test.py即可得到测试结果。

在PTB数据集上，本算法得到的模型ppl值达到 23.81  

本代码均为pytorch官方源码的变动: 
https://github.com/pytorch/examples/tree/master/word_language_model


------------------------------------------------

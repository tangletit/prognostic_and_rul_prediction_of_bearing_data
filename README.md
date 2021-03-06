# Prognostic and Remaining Useful Life Prediction of Bearing

This is the project of hybrid prediction based on deep learning technology.

## Key technology

+ Sparse condition encoding method
+ Shared features modeling with fault prognostic and RUL
+ Data reinforcement

## TODO

+ Increase generality
+ Classification and regression on XJTU bearing dataset
+ Transfer learning appliance
+ Digital twins by Deep Conditional Generative Adversarial Neural Network(DCGAN) 

## Achievements
| Type | Value on Train set | Value on Test set | 
|----|----|----|
| Classification Accuracy | ~99.86% | ~65% |

### Classification result

You can find them in **SVG** file:

+ classification_on_train_data.svg
+ classification_on_test_data.svg

Since they are not intuitive, we didn't publish them on **README.md** file.

### Confusion matrix

+ On train data <br/> ![Confusion matrix on train data](./train_classification_confusion_matrix.svg)
+ On test data  <br/> ![Confusion matrix on test data](./classification_confusion_matrix.svg)

## Train online

**AI studio seems to support only PaddlePaddle framework which is very poor and unfriendly in supporting 1D signal. It will waste a lot of time, so we don't suggest you to use that even they are free.**

<del>You may use Baidu **AI Studio** to train this model by yourself. [\[HERE\]](https://aistudio.baidu.com/aistudio/projectDetail/101595) is the project hosted on **AI studio**.</del>


## Current difficulty

+ Follow Fast-RCNN architecture to design brand-new model

## LICENCE

Project is licensed [MIT](./LICENSE), and XJTU Bearing data is copyrighted by [Biao Wang of Xi'an Jiaotong University](http://biaowang.tech/xjtu-sy-bearing-datasets/)
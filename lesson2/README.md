# fastaiv2keras
This is an implementation in Keras forked from [metachi](https://github.com/metachi/fastaiv2keras) based on the fastai part1 v2 course.
lesson1 and lesson1-finetune2 jupyter notebooks go through the dogs and cats dataset

- lesson1 uses a finetune function that simply freezes early layers and makes the fc layer output predictions for 2 classes
- lesson1-finetune2 uses finetune2 function.  It does a little more trickery to enhance the model.  Note: that our function to find the optimal learning rate (LR_FIND) does not seem to work quite as well when we use finetune2.
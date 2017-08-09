# fast-ai
This is the solution for [Dogs vs Cats competition in Kaggle](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition) instructed by **Jeremy Howard (fastai)** [video](https://www.youtube.com/watch?v=e3aM6XTekJc&t=5474s), [lecture note](http://wiki.fast.ai/index.php/Lesson_2_Notes), [Github](https://github.com/fastai/courses/blob/master/deeplearning1/nbs/dogs_cats_redux.ipynb)

This model takes advantage of [Transfer Learning](http://cs231n.github.io/transfer-learning/) by using pretrained VGG model with vgg16 class and it's run in Keras (Theano as backend).

**Directory structure**
```
fast-ai
│   README.md
│   requirements.txt
|
|---utils
│   │   train.py
|   |   evaluate_next_activity_and_time.py
│   │   evaluate_suffix_and_remaining_time.py
│   │   calculate_accuracy_on_next_event.py
|   |
│---lessons
|   
|---dogs\_vs\_cats:
|   |   data
```

**Data source**
- [Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats)

**Result**
- Score: 0.10174
- Ranking: 263/894

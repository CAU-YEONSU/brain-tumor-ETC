# brain-tumor-ETC-finalproject.
I choose ExtratreesClassification to classify brain tumor.
because I think brain tumor has a lot of randomoble features.
So i think that the best classifier of capture randomoble features is ExtratreesClassifier.
so i choose ExtratreesClassifier(etc).
as i mentioned catch randomoble feature is important so i don't limit max_features, max_depth.
Next I set hyperparameter of etc based on gridsearchcv algorithm.
I set function of parameter, and substitution into gridsearchcv and gridsearchcv's cv=3 to reduce the randomness of the results.
I repeat and repeat this situation.
finally i First catch using 'entropy' is advantage for classify.
i repeat gridsearch again, and set another hyperparameters.
So i set all and fitting the model and the accuracy has out.

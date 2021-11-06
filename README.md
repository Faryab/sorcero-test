# sorcero-test

Report:

I used distill-bert for a smaller transformer based language model.

For the features I concatenated each of the claims and main texts.

I also dropped any labels which were unproven, or had a "-1" label.

This left me with a multiclass classification problem of "true", "false" and "mixture" labels

I used the train//test//dev splits from given dataset.

It took about 2 hours to code up and another 2 hours to train // evaluate the model.

I got about a 70% accuracy on the final test set with the best performing model

If I were to spend more time I would analyze the model predictions to see if it's over//under fitting and how the confusion matrix looks like

All the model checkpoints are in the models.tar.gz file.

(Still adding them to the github repo downloading from colab takes too long...)

=)

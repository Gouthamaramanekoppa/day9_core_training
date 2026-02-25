# day9_core_training
Introduced validation split to monitor model generalization and detect overfitting.

a validation split was introduced during model training to monitor how well the model generalizes to unseen data. Instead of training the model on the entire training dataset, a portion (for example, 20%) was set aside as validation data. This validation data is not used for weight updates but is evaluated after each training epoch.

The purpose of validation is to measure the model’s performance on data it has not directly learned from. While training accuracy shows how well the model fits the training dataset, validation accuracy indicates how well the model can generalize to new inputs.

During training, both training accuracy and validation accuracy were monitored. If training accuracy keeps increasing while validation accuracy stops improving or decreases, it indicates overfitting. Overfitting occurs when the model memorizes training data instead of learning general patterns.

By observing validation loss and validation accuracy trends, it became possible to:

Detect overfitting early

Evaluate model stability

Compare performance across epochs

This step significantly improved understanding of model evaluation and the importance of generalization in machine learning. By the end of Day 9, the model’s learning behavior was analyzed more scientifically rather than relying only on training accuracy.

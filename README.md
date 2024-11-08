Business Forecasting: Assignment 3
 A brief info of what each file is:

 CNN_Model.ipynb- The code that includes the data loader,model,training and weight saving codes
 fashion_mnist_model.pth- file with all the weights
 
 mport_script.py- an import script that takes the weights and gives the accuracy

Following is a summary of the work i have done:
1.
Tried the model in our class.Started with an accuracy of 80%.As the model trained the accuracy slowly increased and then fluctuated btwn 83 and 84.By the end of 20 epochs i got 84.1%.

As i started to change the parameters and the model is going all places.Increasing the learning rate didnt helped me much(atleast for the no of epochs i'm running).But when i Decreased the learning rate, the model started aI did increased the epochs to 30 and halved the batch size.Seeing the model is now crazy,its fluctuating from 85 to 65.But got a 83.3% accuracy finally.

Then i googled to see what people did with fashion MNIST datset in kaeggle

2.Found a "Simple Feedforward Neural Network","Simple Convolutional Neural Network model" and "deeper Convolutional Neural Network model".

Im just making a table so it's easy for reading

| Network     | Epochs | Runtime (minutes) | Accuracy (%) |
|-------------|--------|-------------------|--------------|
| FirstNet    | 20     | 6                 | 84.1         |
| FirstNet    | 30     | 9                 | 83.3         |
| Simple-NN   | 5      | 1                 | 87           |
| Simple-NN   | 20     | 6                 | 88.68        |
| Simple CNN  | 5      | 7                 | 91.62        |
| Simple CNN  | 20     | 19                | 91.69        |
| Deeper CNN  | 5      | 11                | 91.43        |


Since there isn't a big leap in running more epochs in simple cnn, i didnt bother doing it for deeper cnn.I'm gonna go with simple CNN with 5 epochs and call it a day.Since i got 90+ accuracy i think it's okay?

This has been fun

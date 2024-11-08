Business Forecasting: Assignment 3

I'm writing this read me as i'm doing the assingment simultaneously:

1.Tried the model in our class.Started with an accuracy of 80%.As the model trained the accuracy slowly increased and then fluctuated btwn 83 and 84.By the end of 20 epochs i got 84.1%.

Just started to change the parameters and the model is going all places.Increasing the learning rate didnt helped me much(atleast for the no of epochs i'm running).But when i Decreased the learning rate, the model started aI did increased the epochs to 30 and halved the batch size.Seeing the model is now crazy,its fluctuating from 85 to 65.But got a 83.3% accuracy finally.

Now I'm just googling models in pytorch to see if i can get more accuracy.I have all day so might as well just pass time.

2. Found a "Simple Feedforward Neural Network".WOW gave me an accuracy of 87%.
3.Found people in kaeggle using "Convolutional Neural Network model".Got an accuracy of 91.62.
4.Found a "deeper Convolutional Neural Network model".

Im just making a table so it's easy for reading

Network      Epochs   Runtime(minutes)     Accuracy

FirstNet       20          6                 84.1
FirstNet       30          9                 83.3

Simple-NN      5           1                 87
Simple-nn      20          6                 88.68

Simple CNN     5           7                 91.62
Simple CNN     20          19                91.69

Deeper CNN     5           11                91.43

Since there isn't a big leap in running more epochs in simple cnn, i didnt bother doing it for deeper cnn.I'm gonna go with simple CNN with 5 epochs and call it a day.Since i got 90+ accuracy i think it's okay?

This has been fun

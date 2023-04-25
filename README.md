# Explicit-Content-Detection

This project detects NSFW Content and classifies it as Safe or Unsafe for the younger generation especially. We encorporated various algorithms like CNN, Efficient NET V2L and Efficient Net V2M Algorithms and did a comparative analysis between these. This comparative analysis was based on 6 parameters consisitng of Training Accuracy, Testing Accuracy, Loss, Precision, Recall and F1 Score.
The Efficient Net V2L algorithm proved to be the most favourable one for detection of NSFW images in pur project.

Then we also did a comparative study on 5 different optimizers namely: ADAMAX, ADAM, ADAGRAD, ADAMW, and SGD. Each optimizer was tested with Efficient Net V2L algorithm and the outputs were obtained. The ADAMAX turned out to be the best and feasible optimizer as per our requirements.

Followed by this we created a local host system with an amazing design using HTML, CSS and Javascript and got the model into place and utilization of codes using FLASK (model.h5 file). We created an environment where user can check if their images are safe or unsafe for work. If it is unsafe it will not be shown on screen and turned as censored, otherwise if its safe it is shown on the screen it has been written in Python.


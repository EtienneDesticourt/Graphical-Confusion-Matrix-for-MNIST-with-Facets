
# A simple graphical confusion matrix with Facets

Confusion matrices are great to check which classes get confused together, but then you're left to plot, or visualize the wrong examples yourself to figure out why said classes are confusing.  
With Facets the examples can be displayed directly in the confusion matrix as they've shown with the CIFAR dataset:
![CIFAR Confusion Matrix](http://i.imgur.com/AuKVv4z.png "CIFAR Confusion Matrix")  
And you can zoom in on the different classes and better visualize where the problem might lie:  
![CIFAR Confusion Matrix](https://1.bp.blogspot.com/-5hNpUyP5TPs/WWz1HJgS7vI/AAAAAAAAB5Q/s5q_CiGgr3YspPekyjzWLDS981UHFDk4QCLcBGAs/s640/image5.png "CIFAR Confusion Matrix")  

&nbsp;

This repository provides a more thorough example of using Facets to create such a matrix.   
To do so a small CNN is trained on the MNIST dataset using Keras and Tensorflow and a custom function is used to transform the image array into a "sprite atlas" as used by Facets.   

![MNIST Confusion Matrix](http://i.imgur.com/YxShoJD.png "MNIST Confusion Matrix") 
![MNIST Confusion Matrix](http://i.imgur.com/YWVPxNO.png "9s that were misclassified as 4s")  

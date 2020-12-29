# Performance during Training: GPU Task 4

This section explains to students that training is measured by how accurately a model aligns with the real world.
The section introduces the following quantities: training loss, validation loss, and accuracy. Ideally, the values of training and validation loss should decrease from epoch to epoch, although they may jump around some. 

The following points are made using pre trained models to teach the concepts:
* To run more training epochs on an existing model, analogous to a human learner studying more.
* To search the hyperparameter space, analogous to a human learner responding differently to a different teaching style.
* To use the results of others' research, compute, network design, and data, analogous to a human learner copying off an expert

Futhermore, that four aspects of the Neural Nets can manipulate to improve performance. 

1) Data - A large and diverse enough dataset to represent the environment where our model should work. Data curation is an art form in itself.
2) Hyperparameters - Making changes to options like learning rate are like changing your training "style." Currently, finding the right hyperparameters is a manual process learned through experimentation. As you build intuition about what types of jobs respond well to what hyperparameters, your performance will increase.
3) Training time - More epochs improve performance to a point. At some point, too much training will result in overfitting (humans are guilty of this too), so this can not be the only intervention you apply.
4) Network architecture - We'll begin to experiment with network architecture in the next section. This is listed as the last intervention to push back against a false myth that to engage in solving problems with deep learning, people need mastery of network architecture. This field is fascinating and powerful, and improving your skills is a study in math.

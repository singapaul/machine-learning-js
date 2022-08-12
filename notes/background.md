# Why tensor flow JS? 

- It runs in the browser
- Easy access to device features such as the camera
- You can add ML to JS web applications
- Large JS community
- Can import tensorflow into python 
- Let's not talk about JS performance, TS JS is fast, don't worry about it.

## examples in the course 

- linear regression House - price data 
- Binary classification - is house on the waterfront?
- Multiclass classification - how many bedrooms are there?


## Machine learning core concepts

Machine learning is a sub category of AI. We perform tasks without explicitly coded rules. 
- Behaviour is based on data instead of rules.
- Typical ML tasks are around prediction. 
- Alot of the meaning comes from biological learning. 


### core concepts 
- supervised (train model based on existing data e.g. classification) vs unsupervised learning (identify existing patterns e.g. clustering).
- Supervised - split the data set into: training data and testing data. How well does model fit data? We write a loss function.  Typical loss function is mean square error. 


### Artificial neural networks

- inspired by biological neurons. Feed in inputs and they produce outputs. We train via back-propagation using regression. We treat them like a black-box we don't know what is inside but we do tweak the configurations (hyper params)

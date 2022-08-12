# Why tensor flow JS? 

- It runs in the browser
- Easy access to device features such as the camera
- You can add ML to JS web applications
- Large JS community
- Can import tensorflow into python 
- Let's not talk about JS performance, TS JS is fast, don't worry about it.
- JavaScript performance limitations are not as big a concern as you might expect, due to optimised backends using WebGL (in the browser) and native TensorFlow (with Node.js).

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


## Knowledge check
- The original TensorFlow provide APIs for Python, Go, Java & C
- The original TensorFlow does not run in JavaScript and the web browser because native code cannot run in the browser environment.
- TensorFlow.js was created as a distinct but related library to the original TensorFlow. With it it is possible to:
    - Write command-line scripts for ML tasks
    - Integrate ML into a server side back-end
    - Train a ML model in the browser
    - Use ML models created by TF for python
    - Utilise the camera on a smart phone for object recognition


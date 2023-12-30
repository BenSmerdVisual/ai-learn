# What is Deep Learning?
- Regular programming- having an input which then has conditons (rules) put on them and then has an output. 
- deep learning- you have the input and output set and then the deep learning model will figure out the rules itself based on how it can get from the input to the output. (supervised learning)

# Types of Data
- **structured data**- usually in ML like in an excel where theres a lot of labelled data like a table- random forest, tree based algorithm, gradient boostede machine, naive bayes, nearest neightbour, support vector machine
- **unstructurerd data**- data that is not structured and its all over the place, like random text (wikipedia etc)- neural networks, FCNN, CNN, RNN, transformer

# Neural Networks
- Have the inputs (unstructured data)- images, random words, sounds
- Gets converted into numbers- **numerical encoding** and these get put into tensors- [[11, 23, 43], [354, 76, 2], [99, 45, 233]]- like a matrix
- Finds patterns/features/weights to learn representation- this is done by choosing the appropriate neural network for your problem
- **representation outputs**- are the numbers that are output by the nerual networks
- these numerical outputs then get identified by a representation by a human (text)

## Anotmy neural networks
- Input layers- data goes in here
- Hidden layers- learns patterns in here (can be many layers)
- Output layers- outputs learned representation or prediction probabilities
- Each layer ius a combination of linear or non-linear functions


# Types of Learning

## Supervised Learning
- **structured data**- data and labels to implement "rules" for the model to follow
- Means you would have the input and rules to find the ouput

## Unsupercised Learning/Self-supervised
- **unstructurered data**- let the model to figure out the rules based on the input
- give it the input and output and it will figure out the rules
- learns solely on the dat itself by finding patterns etc
## Transfer Learning
- getting the patterns of a dataset and transferring it to another dataset
- basically re-using a model that has been trained on something and then using it on another dataset 

# Use cases
- **sequence-to-sequence (seq2seq)**- having a sequence of input (text or audio) and the sequence output (more text or text recognition from the audio input), (text translation, speech recognition)
- **classification/regression**- regression predicts a number (this can be continous on a arbitrary scale), classification is identifying a categorical aspect (computer vision, NLP)
## Vector
- essentially an array of numbers that represent something within that given vector, eg [123.54, 876.45] can be a vector representation of longitude and latitude for a given coordinate

## Tensor
- Representation of numbers that have the input being numerically encoded, could be a vector, matrix etc
- After tensor has been passed through the neural networks the output will be another tensor and then this gets transformed into human readable output (text most likely)
- input (human readable) -> tensor (computer readable) -> neural network (maths applies to tensor) -> tensor (computer readable) -> output (human readable)
-  A 1D tensor (vector) is simply an array of numbers.
- A 2D tensor (matrix) is an array of vectors (1D tensors).
- A 3D tensor is an array of matrices (2D tensors), and so on.
- The array of numbers can represent specific things eg image a grayscale image can be represented as a 2D tensor (height x width), a color image as a 3D tensor (height x width x color channels), and a video as a 4D tensor (time x height x width x color channels).


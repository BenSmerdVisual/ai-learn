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
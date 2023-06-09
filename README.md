# Handwritten Digit Recognition Model

Here is my attempt at creating my own handwritten digit recognition model using the knowledge I have gained thus far through **Stanford University** and **Deeplearning.ai's** Machine Learning Course. It is a simple multiclass classification neural network that is able to recognize numbers from 0 to 9.

## How to use my model

You can download my notebook called `main.ipynb` and you can see what choices I have made to construct my model (and possibly improve on them). Make sure you have all the required imports!

In addition, you can also check out my `loader.ipynb` notebook where I test the model on new examples, stored in the `digitImages` folder.

## Next Steps
I plan on hopefully improving the model by testing it on different types of layers like Convolutional Layers once I understand how they work. I noticed that the model did not perform that well when I provided my own testing examples (model not generalizing to new examples), which tells me that the model thus far is only good for the Kera's MNIST dataset (perhaps the model overfit).

Additionally, I plan on launching the model on a website so that users can draw images on a $28 \times 28$ pixel canvas and the model will predict what number they drew. My inspiration comes from [this](https://detexify.kirelabs.org/classify.html) website that predicts what $\LaTeX$ symbol the user is looking for.
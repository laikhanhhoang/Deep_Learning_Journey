# Deep Learning Journey

## 📑 Table of Contents

- [📘 About](#-about)
- [📚 Course Content](#-course-content)
- [🧠 What I've Learned](#-what-ive-learned)
- [📖 Supplementary Reading](#-supplementary-reading)
- [🎓 Certificate](#-certificate)

## 📘 About

This repository documents my self-study of Deep Learning through an online Udemy course: **[The Complete Neural Networks Bootcamp: Theory, Applications](https://www.udemy.com/course/the-complete-neural-networks-bootcamp-theory-applications/)** covering core topics like MLP, CNN, RNN, Transformers, and modern applications such as NLP, CV, and LLMs.

## 🧠 What I've Learned

## 📖 Supplementary Reading

## 🎓 Certificate

## 📚 Course content

| Section    | Title            | Summary                                                                                                       | Note and Code                |
|------------|------------------|---------------------------------------------------------------------------------------------------------------|------------------------------|
| 1  | How Neural Networks and Backpropagation Works     | - Theory of Gradient Descent & Propagation<br>- Fwd/Bwd  calculating for a MLP | ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%201%20-%20How%20Neural%20Networks%20and%20Back%20Propagation%20Work.pdf) <br>💻 No |
|2| Loss Functions| - MSE, MAE, Huber Loss, Binary Cross Entropy, Softmax Function, KL Divergence, Hinge Loss, Triplet Ranking Loss <br> - Pros, cons, and real-world applications of the above loss functions| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%202%20-%20Loss%20Functions.pdf) <br>💻 No |
|3| Activation Function| - Sigmoid, Tanh, ReLU, PreLU, ELU, GLU, Swish, Mish <br> - Properties of the above activation functions and their relation to the vanishing gradient problem| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%203%20-%20Activation%20Functions.pdf) <br>💻 No |
|4| Regularization and Normalization| - Regularization techniques: L1, L2, Dropout, DropConnect <br> - Normalization techniques: Min-Max, Standardization, Batch Normalization, Layer Normalization, Group Normalization and PseudoCode for those layers| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%204%20-%20Regularization%20and%20Normalization.pdf) <br>💻 No |
|5| Optimization| - Batch Gradient Descent, SGD, Mini-batch GD, Momentum, RMSProp, SWATS <br> - Regularization, Weight Decay, Decoupling Weight Decay, Adding Decay to SGD and ADAM| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%205%20-%20Optimization.pdf) <br>💻 No |
|6| Hyperparameter tuning and Learning rate Scheduling| - Step decay <br> - Cycling learning rate, Restart, Cosine annealing with Warm Restart| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%206%20-%20Hyperparameter%20tuning%20and%20Learning%20Rate%20Scheduling.pdf) <br>💻 No |
|7|Weight Initialization| - Understanding why initializing all weights to 0 or same value is bad <br> - Normal Distribution, Xavier Initialization, He Norm Initialization and when to use | ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%207%20-%20Weight%20Initialization.pdf) <br>💻 No |
|8|Introduction to Pytorch| - Learning how to use Pytorch tool kits for deep learning: requires_grad, detach, no_grad, loss functions and weight initialization | ✍️💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section8_Introduction_to_Pytorch.ipynb) |
|9|Data Augmentation| Center Crop, Five Crop, Random Resize, Auto Augment, Mixup, Cut mix, Random Augment,...| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%209%20-Data%20Augmentation.pdf) <br>💻 No |
|10| Practical NN in Pytorch with Diabetes Dataset|- Learning how to code end to end a simple Neural Network in Pytoch: how to define batch-size, optimization, loss function,...| 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section10_Apply_NN_in_Diabete.ipynb) |
|11| Visualize the learning process| - Practice coding a neural network with make-moon dataset as did in section 10 and plotting the learning process| 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section11_Visualize_Learning_Process.ipynb) |
|12| Implementing a Neural Network from Scratch with Numpy| Scratch a Neural Network with 3 layers from scratch| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section12_NN_from_scratch.pdf) <br> 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section12_Neural_Network_from_Scratch.ipynb)|
|13| Practical Neural Networks in PyTorch - Application 2: Handwritten Digits| Create an NN that can classify handwritten digits| 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section13_MNIST.ipynb)|
|14| Convolutional Neural Network| Full theoretical explanation of CNN: Shift variance, Pooling, FC, Dropout, Drop Block, Softmax with Temperature|  ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%2014%20-%20CNN.pdf)|
|15| Practical Convolutional Networks in PyTorch - Image Classification| Build and train a simple CNN for MNIST dataset. Also plotting the training accuracy and loss plot| 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section15_Practical_CNN.ipynb)|
|16| CNN Architectures| - Fundamental of famous CNN architectures such as: ResNet, InceptionNet, EfficientNet, DenseNet,... <br> - Transfer Learnign Technique| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%2016%20-%20CNN%20Architectures.pdf)|
|18| Transpose Convolutions| Fundamental of ConvTranspose2d | ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%2018%20-%20Transposed_Convolutions.pdf)|
|19|Transfer Learning in Pytorch - Image Classification| Fine-tuning ResNet18 with data augmentation for accurate ant and bee classification|💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/tree/main/Code/Section19_TransferLearninginPytorch)|
|26| RNN| RNN architecture: simple RNN, LSTM, Bi-LSTM, GRU and their applications| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%2026%20-%20RNN.pdf)|
|21| YOLO Object Detection (Theory)| Fundamental of YOLO (You Only Look Once v1-v2-v3)| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%2021%20-%20YOLO%20Theory.pdf)|
|27| Word Embedding| Why we need word embedding, Cosine Similarity, Word Embedding Model| ✍️ [W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%2027%20-%20Word%20Embedding.pdf) <br> 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section27_Word_Embedding.ipynb)|
|28| Practical Recurrent Networks in PyTorch| Design and code a LSTM model to predict next word| 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section27_RNN_TextGeneration.ipynb)|
|30| Sequence Modelling| Overview of LSTM + attention mechanism application on machine translating and image captioning| ✍️[W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%2030%20-%20Sequence%20Modelling.pdf)|
|31| Practical Sequence Modelling in PyTorch: Chatbot Application| Implementing a chatbot using LSTM + Attention Mechanism from scratch| 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section31_SequenceModelling_Chatbot.ipynb)|
|32| Image Captioning| Implementing a Encoder-Decoder architect using Resnet101 and LSTM Cell for image captioning| 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section32_SequenceModelling_ImageCaptioning/Section32_SequenceModelling_ImageCaptioning.ipynb)|
|33| Transformers|Fundamental of Transformers: Multi-head Attention, Subsequent mask,...| ✍️[W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%2033%20-%20Transformers.pdf)|
|34| Build a Chatbot with Transformer| Implement the chatbot's architecture as shown in section 33| 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/tree/main/Code/Section34_BuildaChatbotwithTransformer)|
|37| BERT| BERT architecture and fine-tune technique| ✍️[W](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Lecture_Note/Section%2037%20-%20BERT.pdf)|
|39| GPTs| Implementing GPT2's architect from scratch| 💻 [Nb](https://github.com/laikhanhhoang/Deep_Learning_Journey/blob/main/Code/Section39_GPT2_implemented_from_scratch.ipynb)|

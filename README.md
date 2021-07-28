# FutureMakers

RESPONSES

Day 1 - 7/6/21

I am new to machine learning and deep learning, but I have always been fascinated by how the human brain works and how our understanding of neuroscience
can be translated into something that a machine can use to intelligently interact with us. In addition to gaining insight into machine learning, I hope to 
use the program to network with people who share similar interests and get a taste of what machine learning is like. I also hope to gain proficiency in 
the common deep learning libraries available today, such as TensorFlow. 

Day 3 - 7/8/21

1. Supervised learning means we are giving the program a known dataset and then the program is trained based with new data and matched to the known target data set. 
Unsupervised learning, on the other hand, doesn't involve any target data. It is simply given some random data and it must then go through and find the pattens/relationships.

2. SciKit learn is focused more on machine learning and data modeling as opposed to data visualization and data analysis. 

Day 4 - 7/9/21

In the midst of the current pandemic, oftentimes, we need to quickly and efficiently diagnose someone with COVID-19 so that we can provide proper isolation 
and prevent the spread of the virus to other healthy individuals. The following dataset offers CT and X-Ray images of both COVID and non-COVID patients. 

https://data.mendeley.com/datasets/8h65ywd2jr/3

Using suprevised machine learning, we can train a program via a classification algorithm so that it can quickly and accurately distinguish between patients with 
COVID-19 and those without COVID-19. This will not provide clinicians with a quick means of evaluating someone for COVID, but can also be used as a screening tool
to help alleviate some of the manual labor in analysing medical images. 

Day 7 - 7/12

1. Tensors are arrays that stores data in multidimensional space. They are used to store and organize data in machine learning. 
2. Unfortunately, due to compatibility issues, I was unable to run the TensorFlow part of the tutorial. 

Day 10 - 7/15

1. The AI algorithm is based on the data that are created by humans. In this case, this data is the hiring data from me during the manual phahse of the game. The algorithm takes this data and tries to fit this model and make future decisions. Unfortunately, if the data itself was biased (ie. I hired more orange people than blue people), then the machine wouldn't know that. If we were to automate the hiring process, it would try to replicate the bias in future hiring decisions. Furthermore, because real ML models have some sort of feedback system, it will just get more and more biased due to the positive feedback loop. 

2. For me, the first thing that stands out is how content is presented on social media sites like Facebook. Gone are the day where everything is presented in chronological order. Instead, special algorithms are used to present users with the most relevant content. While in theory this sounds good, it opens the door for a lot of biases. A key variable that Facebook seems to use to evaluate a post's popularity is the number of likes the post has. The more likes and the more followers the user has, the more likely it is to get recommended. Unfortunately, just because one person has a lot of likes doesn't necessarily mean that it applies to everyone. In fact, due to this, I have missed quite a few important posts from friends who aren't celebrities and unfortunately didn't make the recommendation cut in time for me to see it. I think to make it more fair, the number of likes shouldn't really be used as a variable in deciding what content to recommend to users. 

3. I think the article on the facial recognition systems really highlight how biased input data can lead to biased results. I can speculate that a lot of data used to train the models came from the tech companies themselves, which tends to be light skin and male. It shouldn't come as a surprise then that the algorithms for all 3 companies worked the best for light skin male subjects and did the worst for dark skin female subjects. I think it is important to make sure our training data is generalizable to a large population as a whole before even beginning to build the model. Otherwise, the prediction that the model makes would not really be correct. 

Day 11 - 7/16

A fully connected neural network, as it's name implies, is connected to every neuron in the previous layer and each of those connections has it's own weight. A covolution neural network, on the other hand, gets smaller and smaller through a convolution layer and each layer is only connected to a few neurons in the previous layer. This makes convolution neural networks more efficient and is best used for analyzing images. 

Day 15 - 7/20

A major advantage of using the Rectified Linear Activation function (ReLU) is the fact that is avoids issues caused by the vanishing gradient problem. A sigmoid function is most sensitive to values around 0.5 and a tanh function is most sensitive to values around 0. This means that for very large and very small values, due to this decreased sensitivity, it becomes challenging for the model to learn from itself through backpropogation and improve its performance in subsequent epochs. This vanishing gradient issue is resolved through the use of ReLU functions. In addition, a ReLU function is much less computatationally intensive. With all these considerations, a major use case would be in the hidden layers of a neural network, where values are being passed from one layer to another layer. 

Day 23 - 7/28/21

In terms of ethical implications of big natural language processing models, I think there are a lot of important considerations to make. Because of it's ability to intelligently generate large amounts of text, it is can be easily misused to generate articles with fake stats. This will in turn contirbute to misinformation and with the vast amounts of informations we have out on the internet today, this can lead to a lot of confusion. In addition, it can also be used to generate spam messages and provide other annoyances to people. I do think these models have a lot of potentials and are quite accurate for what they do, but we would probably need some safeguards or guidelines in place to prevent it from being misused. 

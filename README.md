## Fake News Detection

During Hurricane Harvey (2017, Huston), fake news spread quickly on the internet, great amount of people are discussing, doubting and even blaming the government rescue policies. Therefore it is important to develop methods to efficiently detect fake news on social media. In this study, we constructed a neural network model to detect tweets which convey fake news about Hurricane Harvey. Due to the limitation of our dataset, we used a pre-trained GLoVE embedding matrix from [Stanford University](https://nlp.stanford.edu/projects/glove/).

### Architecture

We trained a LSTM network with embedding matrix to detect the fake news during the hurricane, the architecture is shown below.
<p align="center">
  <img src="https://github.com/fangshulin/Fake-News-Detection/blob/master/img/architecture.png" width="400"/></p>

### Reference
Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. GloVe: Global Vectors for Word Representation. 


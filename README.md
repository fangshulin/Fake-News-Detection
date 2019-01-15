## Fake News Detection

During Hurricane Harvey (2017, Huston), fake news spread quickly on the internet, great amount of people are discussing, doubting and even blaming the government rescue policies. Therefore it is important to develop methods to efficiently detect fake news on social media. In this study, we constructed a neural network model to detect tweets which convey fake news about Hurricane Harvey.

### Architecture

We trained a LSTM network with embedding matrix to detect the fake news during the hurricane, the architecture is shown below.
<p align="center">
  <img src="https://github.com/fangshulin/Fake-News-Detection/blob/master/img/architecture.png" width="400"/></p>

### Data
We obtained our unlabeled [raw data](https://digital.library.unt.edu/ark:/67531/metadc993940/) from University of North Texas which contains all "harvey" related tweets during the hurricane. Then we manually labeled them into Fake and True. Due to the limitation of our dataset, we used a pre-trained GLoVE embedding matrix from [Stanford University](https://nlp.stanford.edu/projects/glove/).

### Reference
Sequence Model class from Coursera given by Andrew Ng
Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. 


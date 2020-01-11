# Plant-Disease-Analysis-using-Transfer-Learning
Acknowledgements This dataset was gotten from spMohanty's GitHub Repo  Inspiration This dataset was created for use in my Plant Disease detection System


# Kaggle Dataset
      https://www.kaggle.com/emmarex/plantdisease

# Kaggle Repository
      https://www.kaggle.com/tathagatbanerjee/transfer-learning-based-plant-disease-detection
      
      
      
      
# Hi there ,
This Notebook will deal with an implementation of 5 Layered CNN architecture

## Resnet
## VGG16
## VGG19
## Imagnet Weights are used
## Inception Model
      
 #    Transfer Learning Challenges
Transfer learning has immense potential and is a commonly required enhancement for existing learning algorithms. Yet, there are certain pertinent issues related to transfer learning that need more research and exploration. Apart from the difficulty of answering the questions of what, when, and how to transfer, negative transfer and transfer bounds present major challenges.
1. Negative Transfer: The cases we have discussed so far talk about improvements in target tasks based on knowledge transfer from the source task. There are cases when transfer learning can lead to a drop in performance. Negative transfer refers to scenarios where the transfer of knowledge from the source to the target does not lead to any improvement, but rather causes a drop in the overall performance of the target task. There can be various reasons for negative transfer, such as cases when the source task is not sufficiently related to the target task, or if the transfer method could not leverage the relationship between the source and target tasks very well. Avoiding negative transfer is very important and requires careful investigation. In their work, Rosenstien and their co-authors present empirically how brute-force transfer degrades performance in target tasks when the source and target are too dissimilar. Bayesian approaches by Bakker and their co-authors, along with other techniques exploring clustering-based solutions to identify relatedness, are being researched to avoid negative transfers.
2. Transfer Bounds: Quantifying the transfer in transfer learning is also very important, that affects the quality of the transfer and its viability. To gauge the amount for the transfer, Hassan Mahmud and their co-authors used Kolmogorov complexity to prove certain theoretical bounds to analyze transfer learning and measure relatedness between tasks. Eaton and their co-authors presented a novel graph-based approach to measure knowledge transfer. Detailed discussions of these techniques are outside the scope of this article. Readers are encouraged to explore more on these topics using the publications outlined in this section!

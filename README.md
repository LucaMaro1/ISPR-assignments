# ISPR-assignments
"Intelligent Systems for Pattern Recognition" assignments, University of Pisa, A.A. 2021-2022

<br>

## Assignment 1
Extracting <b>SIFT descriptors</b> using the visual feature embedded in SIFT, to identify the <b>points of interest</b>. <br>
On the aggregated descriptors a clustering is performed, using <b>k-means</b>, to have a descriptors partitioning. <br>
Finally results are analysed and discussed.
<br>

## Assignment 2
Image understanding application using <b>LDA</b> model and the <b>bag of visual terms</b> approach. <br>
At first, <b>SIFT descriptors</b> are clustered using <b>k-means</b> to create a bag of visual terms. Then <b>LDA</b> models are trained on the corpus of key points. A grid search is permed using <b>coherence score</b> as evaluation metric.<br>
Finally weaknesses and strenghts of this approach are discussed, looking at the acquired results.
<br>

## Assignment 3
Implementation of a <b>Deep Learning</b> approach on the task given by the <b>CIFAR-10</b> dataset. <br>
The architecture of the model corresponds to the <b>Slimmed ResNet18</b> defined in the paper "Gradient Episodic Memory for Continual Learning" by Lopez et al. <br>
Training was performed running a grid search over a 5-fold cross validation. After that, the 5 models obtained are combined to create an <b>ensemble</b>. <br>
An additional <b>occlusion experiment</b> was performed using 4x4 and 8x8 sliding patches over the images. <br>
Finally, a summary of the results is provided, where the behaviour of the model is discussed refearing both to the use or not of the occlusions.

[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

This capstone project will investigate dog breed identification and build an algorithm to produce an estimation of a dog breed given a dog image or dog breed that best ensembles the provided human image. Given an image of a dog, the algorithm will identify an estimate of the breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]


## Project Materials

### dog_app.ipynb

The file is cloned from the Udacity repository with commend shown below:
	
	```	
		git clone https://github.com/udacity/deep-learning-v2-pytorch.git
		cd deep-learning-v2-pytorch/project-dog-classification
	```
The jupyter notebook contains exploratory data analysis, implementation of CNN model from scratch, and the final app algorithm using resnet101 model for dog breed classification. 

	```
		jupyter notebook dog_app.ipynb
	```
Sample outputs are shown below:

```
Hello, human!
```
![image](https://user-images.githubusercontent.com/24922489/124483634-cc117c00-dd67-11eb-811a-cd4e9b98844c.png)

```
You look like a ...
Top 1 breed: Cardigan_welsh_corgi, class probability: 0.02444
Top 2 breed: Boxer, class probability: 0.02280
Top 3 breed: Afghan_hound, class probability: 0.01836
```

```
Hello, dog!
```
![image](https://user-images.githubusercontent.com/24922489/124483701-dfbce280-dd67-11eb-898c-f97538d2cc6c.png)

```
Top 1 breed: Doberman_pinscher, class probability: 0.98857
Top 2 breed: German_pinscher, class probability: 0.00815
Top 3 breed: Great_dane, class probability: 0.00163
```

### Proposal.pdf
Project proposal outlined the scope and goals for the proposal. The document discussed the models will be implemented in the project and outlined the metrics to measure model performance and benchmarks used to assess model's adequacy.

### Project Report.pdf
Project report documented the model development process in detail. It included the model testing results and detailed implementation steps of the models. Specifically, for the dog classification models (from scratch and transfer learning), model training output, i.e. training loss vs valiation loss, was analyzed; and the accuracy of each model was compared. In addition, F1 score for each breed was calculated and discussed. Lastly, the project report also discussed further improvements for this project.


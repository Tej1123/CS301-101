# CS301-101

**Facial Emotion Recognition and Detection**

**What is the problem that you will be investigating? Why is it interesting?**

  From the time that technology has become part of our lives, it has come with constant discussions about improving security. Facial recognition is a program/ system that is used in different ways for reasons that pertain to: security, marketing, social media, and tracking. Other than fingerprint scanners, facial recognition is a relatively unique method that aims to read the face and be able to judge the expression, whether the face is a match, or adjust for an expression depending on the face. The ability of a program to adhere to the normal skills of a human is unusual and important to understand.

**What reading will you examine to provide context and background?**

  Security details are important readings to comprehend why to use facial recognition, while programming journals can provide insight into how facial recognition works. Most times any questions that pertain to the problem can be found online and through that read any of the solutions. 

**What data will you use? If you are collecting new data, how will you do it?**	

  The data that will be used for our project will be extracted from an online repository that contains hundreds of data sets for different types of data science problems. The data set will have information regarding features of images such as pose, expression, eyes (sunglasses or not) and size.

**What method or algorithm are you proposing? If there are existing implementations, will you use them and how? How do you plan to improve or modify such implementations? You don’t have to have an exact answer at this point, but you should have a general sense of how you will approach the problem you are working on.**

  We will use an appearance-based model for this project. Each image in the data set will be considered as a high dimensional vector. We will have several feature spaces regarding each image. The sample image will be compared to the training set. We will either classify this method as linear or nonlinear. 

**How will you evaluate your results? Qualitatively, what kind of results do you expect (e.g. plots or figures)? Quantitatively, what kind of analysis will you use to evaluate and/or compare your results (e.g. what performance metrics or statistical tests)?**

  We will evaluate our results by a quantitative metric. We will be focusing on accuracy and efficiency by minimizing our loss function as well as minimizing loading time. We will be separating our data into, analyzing the different types of emotions a person might have, another data would be, their facial structure. These categories will have different bases and cannot be analyzed in the same context. In doing this we will be able to measure our algorithm using three different metrics, based on the difficulty to predict correctly.

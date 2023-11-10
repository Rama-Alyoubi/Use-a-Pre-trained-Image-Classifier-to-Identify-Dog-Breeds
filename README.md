# Use a Pre-trained Image Classifier to Identify Dog Breeds

## Description:

To streamline the citywide dog show registration process, I used a pre-trained image classifier to identify dog breeds. Participants submit dog images, and the classifier accurately tags the breeds. My goal is to organize a fair and enjoyable event that showcases the diverse range of dog breeds in our city.

## Tasks:
Using my Python skills, I aimed to determine which image classification algorithm works the "best" on classifying images as "dogs" or "not dogs". I also wanted to evaluate how well the "best" classification algorithm performs in correctly identifying a dog's breed. An image classifier is simply a tool with an input and an output, where the input is an image and the output determines what the image depicts, such as a dog. It's important to note that image classifiers may not always categorize images correctly. Additionally, I timed the runtime of each algorithm to consider the trade-off between accuracy and runtime.

## Principal Objectives:
1. Correctly identify which pet images are of dogs, even if the breed is misclassified, and which pet images aren't of dogs.
2. Accurately classify the breed of dogs in the images that are indeed dogs.
3. Determine which CNN model architecture, out of ResNet, AlexNet, and VGG, achieves the best results for objectives 1 and 2.
4. Take into account the time resources required to accomplish objectives 1 and 2 and assess if an alternative solution could have provided a "good enough" result given the runtime of each algorithm.

## Results Table:
Throughout the project, I focused on two main objectives: identifying which pet images are dogs and which aren't, and classifying the breeds of dogs in the images that are indeed dogs.

Based on the results, the "best" model architecture is VGG. It outperformed both ResNet and AlexNet when considering both objectives 1 and 2. While ResNet displayed better accuracy in dog breed classification compared to AlexNet, only VGG and AlexNet achieved a perfect 100% accuracy in classifying "dogs" and "not-a-dog". Specifically, VGG achieved 100% accuracy in classifying "dogs" and "not-a-dog", and it also demonstrated the best performance in breed classification with an impressive accuracy of 93.3%.

![t Architecture](https://github.com/Rama-Alyoubi/Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds/assets/128150728/787042bc-e38e-4e7c-ae2b-5bb38f34c175)]

![V Architecture](https://github.com/Rama-Alyoubi/Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds/assets/128150728/a5623b31-6a8b-47e8-91da-030f9b8a78f5)]

![A Architecture](https://github.com/Rama-Alyoubi/Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds/assets/128150728/e975eda9-3fcd-4c25-9b95-206108eff0fe)]

![R Architecture](https://github.com/Rama-Alyoubi/Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds/assets/128150728/16684beb-3656-4d0f-91c2-60abedcd3a8d)]




## Acknowledgment:
I would like to acknowledge that this project is the first project completed as part of the AI Programming with Python Nanodegree provided by Udacity. The project was created by Jennifer, a statistician and computer scientist who previously worked as a professor at Florida Polytechnic University.
- Feel free to explore the project further and experiment with alternative solutions to balance accuracy and runtime based on your specific requirements. Happy coding!

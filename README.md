# Final-Project-Image-Classification-using-CNN-for-Waste-Bags

<h2>Introduction</h2>
<p>This project develops an image classification model using deep learning to distinguish between three types of waste bags: plastic bags, paper bags, and garbage bags. We leverage a Convolutional Neural Network (CNN) to learn visual features that characterize each bag category. By training on a labeled dataset of bag images, the CNN will learn to automatically identify the bag type in new images. Such a model has practical applications in recycling and waste management systems. For example, automatically sorting trash or recyclables by bag type could improve efficiency in waste processing. Overall, this project demonstrates the effectiveness of CNNs in image recognition tasks and contributes toward smarter environmental sustainability solutions.</p>

<p>The dataset used in this project consists of synthetic images of plastic, paper, and garbage bags (sourced from <a href="https://www.kaggle.com/datasets/vencerlanz09/plastic-paper-garbage-bag-synthetic-images/data">Kaggle</a>). The data is organized into three folders, one for each class of bag, each containing thousands of images. In total, there are 15,000 images – with 5,000 images per class.</p>
<p>We first split this dataset into training, validation, and test sets to facilitate model development and evaluation:</p>
<ul>
  <li><strong>Training set:</strong> Used to train the CNN (learn model parameters).</li>
  <li><strong>Validation set:</strong> Used during training for tuning (to check the model’s performance on unseen data and prevent overfitting).</li>
  <li><strong>Test set:</strong> Held‑out data to evaluate the final model performance.</li>
</ul>
<p>For a balanced split, we allocate 40% of the images of each class to training, 20% to validation, and 40% to testing. This results in roughly 2,000 images per class for training, 1,000 per class for validation, and 2,000 per class for testing. We ensure each subset contains an equal distribution of the three classes.</p>

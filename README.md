# Chest-X-Ray-Classification
A CNN designed to effectively differentiate between chest X-rays showing normal conditions and those exhibiting indications of pneumonia.

Dataset Link : [Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

<ul>
  <li>
The machine learning project created by the individual focused on pneumonia detection in chest X-rays. Employing data augmentation and image preprocessing techniques, the project aimed to enhance image quality and reduce noise in the dataset.
  </li>
  <li>
Image preprocessing encompassed various methods, including median filtering, CLAHE (Contrast Limited Adaptive Histogram Equalization), and grayscaling. These techniques collectively improved image clarity and quality, allowing the model to identify pneumonia indicators more effectively.
</li>
  <li>
Data augmentation played a crucial role in enhancing model generalization. Techniques such as rescaling, zooming, shifting, and rotating were employed to diversify the dataset. This approach ensured the model's adaptability to different orientations and image sizes.
</li>
  <li>
The project featured a custom-designed CNN architecture consisting of 7 blocks. Each block contained a Conv2D layer, a MaxPool2D layer, and a Dropout layer. This architecture balanced feature extraction and regularization, contributing to the model's efficient learning.
</li>
  <li>
To optimize hyperparameters, the project incorporated strategies such as logging, checkpointing, and a learning rate scheduler. These techniques facilitated systematic hyperparameter tuning, resulting in a refined model.
</li>
  <li>
Additionally, the project integrated Grad-CAM (Gradient-weighted Class Activation Mapping) to gain insights into the model's decision-making process. Grad-CAM visualizations highlighted significant areas in X-ray images, providing clarity on the features influencing the model's predictions.
</li>
  <li>
The project's cumulative efforts yielded impressive results, with the final model achieving an accuracy of 97.11% and a precision of 98%. This performance underscored the model's efficacy in distinguishing between normal and pneumonia-indicative chest X-rays.
</li>
</ul>

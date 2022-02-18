# Exploiting Correlation Between Model Accuracy and Explanation Quality

In this project, we have investigated the correlation between model accuracy and explanation quality on a new dataset. The project is based on this paper

*Studying and Exploiting the Relationship Between Model Accuracy and Explanation Quality;* By Y. Jia, E. Frank, B. Pfahringer, A. Bifet, and N. Lim.

We have written the code from scratch and build our own dataset. Our dataset contains 300 images, out of which 120 are positive images containing apples and 180 images are negative containing other types of fruit other than apples. Also this dataset contains a directroy ``expl``, which contains positive images without background (only the part of the image which includs apple is kept). These kind of images are called *expert explanations* by the authors of the paper, and are necessary for calculating the explanation quality.

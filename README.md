# TensorFlow Bijectors
- In this project, I explored how to use TensorFlow Probability Bijectors to transform distributions and perform operations on them.
- You can get the code in [tensorflow_bijectors.ipynb](./tensorflow_bijectors.ipynb)

## Bijector Basics
- We started with basic bijectors like `Exp` and `Affine`. Bijectors allow transforming base distributions such as a standard normal distribution into more complex ones by applying mathematical transformations.

- Sampling from the distribution before applying bijectors.

![Sample](./screenshots/sample.JPG)


- Sampling from the distribution after applying `Shift` and `Scale` bijectors. (notice the axis values)

![Sample](./screenshots/scale_and_shifted_sample.JPG)


- Using `Softfloor` bijector:

![softfloor](./screenshots/softfloor.JPG)

- Using `GumbelCDF` bijector:

![softfloor](./screenshots/gumbell.JPG)


### Exponential Bijector:
- Used an exponential bijector to transform the distribution.

- Transformation applied to a normal distribution to stretch it exponentially.

![Exp Bijector](./screenshots/exp.JPG)


### Example of a Cubic Bijector:
- This example applies a cubic transformation to a normal distribution.

- Forward transformation using the cubic bijector.

![Cubic](./screenshots/cubic.JPG)

- The determinant of the forward transformation.

![Cubic Forward Determinant](./screenshots/cubic_forward_det.JPG)

- The inverse transformation.

![Cubic Inverse](./screenshots/cubic_inv.JPG)

- The determinant of the inverse transformation.

![Cubic Inverse Determinant](./screenshots/cubic_inv_det.JPG)


### Normalizing Flow with Mixtures:
- Demonstrated how to train a normalizing flow model with a Gaussian mixture model.

- Visualization of a mixture of Gaussians before training.

![Mix Gaussian](./screenshots/mix_gauss.JPG)

- The Gaussian mixture before training the model.

![Non-trained Mix Gaussian](./screenshots/non_trained_mix_gauss.JPG)

### Training and Evaluation:
- Trained the bijector model and visualized its results.

- The training process for the bijector model.

![Training Process](./screenshots/training.JPG)


### Sampling and Data Transformation:
- Showcased sampling and transformation of distributions using trained bijectors.

- Comparison of normal and masked distributions.

![Normal vs Masked](./screenshots/normal_vs_masked.JPG)

- The sample after applying normalization.

![Normalizing Sample](./screenshots/normalizing_sample.JPG)


### Masked and Permuted Distributions:
- Demonstrated how masked and permuted bijectors modify distributions.

![After Training Masked](./screenshots/after_training_masked.JPG)
- Masked distribution after training.

![Masked Contour](./screenshots/after_training_masked_contour.JPG)
- Contour plot of the masked distribution.

![Masked Data](./screenshots/after_training_masked_data.JPG)
- Data points of the masked distribution.

![After Training Permuted](./screenshots/after_training_permuted.JPG)
- Permuted distribution after training.

![Permuted Contour](./screenshots/after_training_permuted_contour.JPG)
- Contour plot of the permuted distribution.

![Permuted Data](./screenshots/after_training_permuted_data.JPG)
- Data points of the permuted distribution.


## Setup
- Create virtual environment: `python -m venv venv`
- Activate virtual environment: `call venv/Scripts/activate.bat` in cmd
- Install dependencies: `pip install -r requirements.txt`

# Libraries
- TensorFlow
- TensorFlow Probability
- Matplotlib

## Contact
- LinkedIn: [Natan Asrat](https://linkedin.com/in/natan-asrat)
- Gmail: nathanyilmaasrat@gmail.com
- Telegram: [Natan Asrat](https://t.me/fail_your_way_to_success)
- Youtube: [Natville](https://www.youtube.com/@natvilletutor)

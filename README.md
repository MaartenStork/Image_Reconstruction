# Image Reconstruction Techniques Repository

This repository explores various **image reconstruction methods**, providing a comparative look at different, possible approaches.

## Overview

The repository includes four image reconstruction techniques:

1. **Fourier Transform Reconstruction**
   - Uses **2D Fourier Transform** to decompose an image into frequency components and reconstruct it by progressively adding frequencies.

2. **Wavelet Transform Reconstruction**
   - Applies **discrete wavelet transform** for multi-resolution analysis, enabling efficient reconstruction of both coarse and fine image details.

3. **Compressed Sensing Reconstruction**
   - Uses **random sampling** and **L1 minimization** to reconstruct images from incomplete data, leveraging sparsity in the transform domain.

4. **Autoencoder-Based Reconstruction**
   - Uses a **convolutional autoencoder** to encode an image into a lower-dimensional latent space and reconstruct it, minimizing reconstruction error via backpropagation.

## Usage
1. **Install Dependencies**:
   ```sh
   pip install numpy matplotlib opencv-python scikit-image tensorflow pywavelets
   ```
2. **Run Scripts**: Each reconstruction method is in a separate script:
   ```sh
   python fourier_transform_reconstruction.py
   ```

## License
Licensed under the MIT License.

## Contact
For questions or suggestions, feel free to reach out or open an issue.

Happy reconstructing!

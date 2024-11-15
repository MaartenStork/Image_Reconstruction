# Image Reconstruction Techniques Repository

This repository explores various **image reconstruction methods**, providing a comparative look at different, possible approaches.

## Overview

The repository includes four image reconstruction techniques:

1. **Fourier Transform Reconstruction**
   - Uses **frequency components** to reconstruct images, demonstrating the contribution of different frequencies to image formation.

2. **Wavelet Transform Reconstruction**
   - Provides **localized frequency analysis** using wavelets, allowing for efficient reconstruction of details and edges.

3. **Compressed Sensing Reconstruction**
   - Reconstructs images from **incomplete data** using sparsity and optimization techniques, often used in **medical imaging**.

4. **Autoencoder-Based Reconstruction**
   - Uses a **neural network** to learn compressed representations and reconstruct images, demonstrating the power of deep learning.

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

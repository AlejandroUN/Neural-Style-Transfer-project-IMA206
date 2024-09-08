# Neural Style Transfer: Transferring Painting Styles

This repository contains an implementation of **Neural Style Transfer**, allowing users to apply the stylistic elements of famous paintings to photographic images while retaining the original color palette of the content images. The project is based on **Gatys et al.**'s algorithm with key modifications to improve color retention and flexibility.

![image](https://github.com/user-attachments/assets/b475fd45-ae66-4db5-89be-3709df3f4325)



## Project Overview

This project uses **Convolutional Neural Networks (CNNs)** to merge the content of one image with the style of another. We extend traditional methods by introducing a pre-transfer color alignment process to retain the color integrity of the content image, enabling robust and artistic image transformations.

### Key Features:
- **Style Transfer:** Transforms a content image into a new image by applying the style of a famous painting.
- **Color Retention:** Preserves the original color palette of the content image using a color alignment process.
- **Customizable Style and Content Weights:** Fine-tune the balance between style and content using adjustable hyperparameters.


### Final Report:
[Final Report Link](https://github.com/AlejandroUN/Neural-Style-Transfer-project-IMA206/blob/main/final_report.pdf)

### Technologies:
- Python
- PyTorch (for neural network implementation)
- ADAM optimizer (for optimization)
- VGGNet-19 (pre-trained on ImageNet)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

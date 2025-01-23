# Stipple Art Generation AI

This repository contains a project for generating stippled art using Generative Adversarial Networks (GANs). The project processes input images and produces stippled art outputs, showcasing the potential of AI in artistic design and creative fields.

---

## Features

- **Input Images**: A variety of sample images (e.g., animals, objects, abstract shapes) provided in the `data/input_images` folder.
- **Output Examples**: Generated stippled art images stored in the `output/generated_images` folder.
- **GAN Implementation**: Deep learning model implemented for converting images into stippled art style.
- **Notebook**: `src/StippledArtGeneration.ipynb` contains the training and generation process in an interactive format.

---

## Folder Structure

```
StippleArtGenerationAI/
├── gan-stippling/
│   ├── data/
│   │   ├── input_images/       # Sample input images
│   ├── output/
│   │   ├── generated_images/   # Generated stippled art outputs
│   ├── src/
│   │   ├── StippledArtGeneration.ipynb  # Main implementation
│   ├── requirements.txt       # List of Python dependencies
│   ├── .gitignore             # Git ignore file
├── .DS_Store (macOS metadata)
```

---

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- Python 3.8 or later
- pip (Python package manager)
- GPU with CUDA support (recommended for faster processing)

### Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/StippleArtGenerationAI.git
   cd StippleArtGenerationAI/gan-stippling
   ```

2. **Install Dependencies**
   Install the required Python packages from the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the Dataset**
   Ensure the `data/input_images/` folder contains the input images you want to process.

---

## Usage

1. **Run the Jupyter Notebook**
   Open the `src/StippledArtGeneration.ipynb` notebook using Jupyter or any other compatible IDE:
   ```bash
   jupyter notebook src/StippledArtGeneration.ipynb
   ```

2. **Train the Model**
   Follow the steps in the notebook to train the GAN model on the provided dataset.

3. **Generate Stippled Art**
   Use the trained model to generate stippled art from the input images. The outputs will be saved in the `output/generated_images/` folder.

---

## Examples

### Input Images

The project includes a variety of input images stored in the `data/input_images/` folder, such as:

- Whale
- Elephant
- Angry Bird
- Rocket

### Output Examples

The `output/generated_images/` folder contains generated examples, such as:

- `image_at_epoch_0047_0.png`
- `image_at_epoch_0049_4.png`

![Sample Output](output/generated_images/image_at_epoch_0048_0.png)

---

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve this project.

---

## Acknowledgments

- Inspiration from artistic GAN applications
- Sample datasets and images used for training and testing

---

Happy stippling!


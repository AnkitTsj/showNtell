# Show and Tell: Image Captioning Model

This repository contains an implementation of the **Show and Tell** paper, which introduced an early approach to Vision-Language Models (VLMs) using a CNN-LSTM architecture for image caption generation.

## Overview
- Implemented as part of a learning exercise based on the original paper.
- Uses **CNN (for feature extraction) + LSTM (for sequence generation)**.
- Aimed at understanding early fusion of vision and language models.
- Suitable for beginners to VLMs who want to see the basics in action.

## Features
- Implements the **Show and Tell** architecture as described in the paper.
- Uses **COCO train2017** dataset for training.
- Trained for **10 epochs** with a **batch size of 3600**.
- Provides a simple inference setup in a **Jupyter Notebook**.

## Requirements
Install the required dependencies using:
```bash
pip install torch torchvision pillow json
```

## Running the Model
### Training
1. Ensure COCO dataset paths are correctly set.
2. Run the training script (modify paths if necessary).

### Inference
- Open the provided Jupyter Notebook.
- Load a trained model checkpoint.
- Run inference to generate captions for new images.

## Results
- The model generates image captions based on extracted CNN features and LSTM-based sequence generation.
- Verified correctness by comparing outputs to the original paper.

## Notes
- No advanced optimizations were performed; this is a direct implementation of the paper.
- Contributions are not required as this was a personal learning project.
- No licensing since this is not intended for public or production use.

## Acknowledgments
- This is part of paper series implementation [skalsikp’s repo on VLMs](https://github.com/SkalskiP/vlms-zero-to-hero).
- Based on the **Show and Tell** paper. (https://arxiv.org/pdf/1411.4555)


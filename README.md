# Text-to-Image Generation using AI/ML

## Project Overview

This project is a **Text-to-Image Generation** application developed using **Artificial Intelligence (AI)** and **Machine Learning (ML)** techniques. The application takes a text input and generates a related image based on the description provided. The goal of the project is to convert text descriptions into realistic images using the **Stable Diffusion** model, which is a powerful deep learning model for generating high-quality images.

## Key Technologies Used

- **Gradio**: A user-friendly library that enables the creation of interactive interfaces for machine learning models. I used Gradio to build an intuitive front-end interface for users to input text and view generated images instantly.
  
- **Stable Diffusion**: A state-of-the-art model for generating detailed images from textual descriptions. The model uses a deep learning architecture to understand the text and generate realistic images based on it.

## Features

- **Text Input**: Users can input any text description.
- **Image Generation**: Based on the text, the system generates an image that matches the description.
- **Interactive UI**: The application has an easy-to-use interface via Gradio, making it simple for users to interact with the model and visualize their descriptions.

## Installation

### Prerequisites

Before you start, ensure you have the following installed:
- Python 3.x
- Gradio
- Stable Diffusion model and necessary libraries (`torch`, `transformers`, etc.)

### Step-by-step Instructions

1. **Clone the Repository**:
    ```bash
    git clone <repository-url>
    cd <project-directory>
    ```

2. **Run**:
    ```bash
    Image_gen.ipynb
    ```
    This will run the project, and you can access the application via your browser in Google colab or Jupyter.

3. **Start Generating Images**:
    - Open the provided link in your browser.
    - Enter a text description in the input box.
    - Click on the "Generate Image" button to view the corresponding image.

## How It Works

1. **Text Input**: The user provides a text description (e.g., "a dog playing in the park").
2. **Preprocessing**: The description is tokenized and processed by the Stable Diffusion model.
3. **Image Generation**: The model generates a realistic image based on the given description.
4. **Output**: The generated image is displayed for the user.

## Example

Here is an example of how you can use the system:

- **Input**: "A cat sitting on a windowsill, looking out at the sunset."
- **Output**: A realistic image of a cat sitting on a windowsill during a sunset.

## Glimpse of the project

![alt text](https://github.com/sidra-quadri/image/blob/cd627fcdb104cdb561ca1a44da418e61ffa7faa8/img1.png)
<br><br>

![alt text](https://github.com/sidra-quadri/image/blob/cd627fcdb104cdb561ca1a44da418e61ffa7faa8/imgRe.png)

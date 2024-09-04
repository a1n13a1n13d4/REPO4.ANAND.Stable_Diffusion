# Stable Diffusion AI

Welcome to the Stable Diffusion AI repository. This project implements a deep learning-based approach to generate high-quality images using diffusion models. Stable Diffusion AI is built to handle complex image generation tasks with high efficiency and flexibility.

## Repository

[GitHub Repository Link](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

## Overview

Stable Diffusion AI is a cutting-edge machine learning model that leverages diffusion processes for generating images. It has been designed to provide high-quality, high-resolution images while being computationally efficient.

**Note:** This is an open-source project. I use and run this as part of my internship. The project is freely available for anyone to use, modify, and contribute to. Here, through the [Readme.md](https://github.com/a1n13a1n13d4/Repo4.ANAND.Stable_Diffusion/blob/main/README.md), I share my experience in running the Stable Diffusion Model.

## Features

- **High-Quality Image Generation:** Generate realistic images with impressive details.
- **Efficient Computation:** Optimized for speed and resource usage.
- **Flexible Configuration:** Customize the model settings to suit various use cases.

## Requirements

Before setting up the environment, ensure you have the following:

- **Python Version:** Python 3.8 or later is recommended.
- **Virtual Environment:** It is advised to use a virtual environment to manage dependencies.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git
   cd stable-diffusion-webui
   ```

2. **Set Up Virtual Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**

   Install all the necessary dependencies by running:

   ```bash
   pip install -r requirements.txt
   ```

## Dependencies

Here are some of the key dependencies required by the project:

- **Accelerate:** 0.21.0
- **AIOFiles:** 23.2.1
- **AIOHTTP:** 3.10.5
- **Albumentations:** 1.4.3
- **Altair:** 5.4.1
- **AnyIO:** 3.7.1
- **FastAPI:** 0.94.0
- **Gradio:** 3.41.2
- **OpenCV:** cv2
- **PyTorch:** The project utilizes PyTorch as the primary deep learning framework.
- **GitPython:** 3.1.32
- **Cython:** 3.0.11
- **FlatBuffers:** 24.3.25
- **Matplotlib:** For visualization purposes.

## Download Model Files

To get started with Stable Diffusion AI, you need to download the necessary model files:

1. **Primary Models:**
   - [v1-5-pruned-emaonly-fp16.safetensors](https://huggingface.co/CompVis/stable-diffusion-v-1-4-original)
   - [v2-1_768-ema-pruned.safetensors](https://huggingface.co/stabilityai/stable-diffusion-2-1)

2. **Additional Resources:**
   - For more models and updates, check out the following resources:
     - [Hugging Face Stable Diffusion Collection](https://huggingface.co/CompVis)
     - [Stable Diffusion Official Website](https://stability.ai/stable-diffusion)
     - [Model Overview and Documentation](https://stability.ai/research/stable-diffusion-models)

   Save the downloaded models to the appropriate directory in your project:

   ```text
   D:\Machine_Learning_DiffuseAi\Project\Stable\models\Stable-diffusion\
   ```

## Running the Model

To run the Stable Diffusion AI model, use the following command:

```bash
python src/main.py
```

This command will execute the main script that initializes the model and begins the image generation process.

## Running the Web UI

1. **To Install and Run the Stable Diffusion AI easily:**
   - Navigate to the project directory:
     ```bash
     cd Directory Path\Stable-Diffusion
     ```
   - Run the web UI by executing:
     ```bash
     webui.bat
     ```
   - This will install any remaining dependencies and start the Stable Diffusion interface.

2. **Accessing the Web UI:**
   - Once the setup is complete, open your web browser and go to `http://localhost:7860` to start using Stable Diffusion.

## Contributions

Contributions are welcome! If you have suggestions or find any issues, please feel free to submit a pull request or open an issue on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or support, please contact me via email at [sanand03027005@gmail.com](mailto:sanand03027005@gmail.com?subject=Enquiry%20about%20Running%20Stable%20Diffusion%20AI) or connect with me on [LinkedIn](https://www.linkedin.com/in/anands37/).


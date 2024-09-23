# Stable Diffusion AI

Welcome to the Stable Diffusion AI repository. This project implements a deep learning-based approach to generate high-quality images using diffusion models. Stable Diffusion AI is built to handle complex image generation tasks with high efficiency and flexibility.

## Repository

[GitHub Repository Link](https://github.com/a1n13a1n13d4/REPO4.ANAND.Stable_Diffusion/)

## Overview

Stable Diffusion AI is a cutting-edge machine learning model that leverages diffusion processes for generating images. It has been designed to provide high-quality, high-resolution images while being computationally efficient.

**Note:** This is an open-source project that I use and run as part of my internship. The project is freely available for anyone to use, modify, and contribute to. 

So, I used the [AUTOMATIC1111's stable-diffusion-webui repository](https://github.com/AUTOMATIC1111/stable-diffusion-webui) as a base and updated the UI to feature a **Black Theme** for a more modern and visually appealing interface.

## Features

- **High-Quality Image Generation:** Generate realistic images with impressive details.
- **Efficient Computation:** Optimized for speed and resource usage.
- **Customizable UI:** Updated with a **Black Theme** for an improved user experience.
- **Flexible Configuration:** Customize the model settings to suit various use cases.

## Requirements

Before setting up the environment, ensure you have the following:

- **Python Version:** Python 3.10.6 is required for running this project.

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/a1n13a1n13d4/REPO4.ANAND.Stable_Diffusion.git
cd REPO4.ANAND.Stable_Diffusion
```

### Step 2: Run `webui.bat` (With Internet Connection)

Run the `webui.bat` script to automatically install all required dependencies and set up the necessary files, models, and interfaces. Ensure you have a stable **internet connection**.

```bash
webui.bat
```

This will handle the entire setup process, including downloading the necessary models, installing dependencies, and starting the interface.

> **Important**: Make sure **Python 3.10.6** is installed before running the web UI.

---

## Dependencies

Here are some of the key dependencies automatically installed when running the `webui.bat`:

- **Accelerate** 0.21.0
- **AIOFiles** 23.2.1
- **AIOHTTP** 3.10.5
- **Albumentations** 1.4.3
- **Altair** 5.4.1
- **AnyIO** 3.7.1
- **FastAPI** 0.94.0
- **Gradio** 3.41.2
- **PyTorch** (core deep learning framework)
- **OpenCV** (cv2)
- **GitPython** 3.1.32
- **Cython** 3.0.11
- **FlatBuffers** 24.3.25
- **Matplotlib** (for visualization)

---

## Download Model Files

To get started with Stable Diffusion AI, you need to download the necessary model files:

1. **Primary Models:**
   - [v1-5-pruned-emaonly-fp16.safetensors](https://huggingface.co/CompVis/stable-diffusion-v-1-4-original)
   - [v2-1_768-ema-pruned.safetensors](https://huggingface.co/stabilityai/stable-diffusion-2-1)

2. **Additional Resources:**
   - For more models and updates, check out the following resources:
     - [Hugging Face Stable Diffusion Collection](https://huggingface.co/CompVis)
     - [Stable Diffusion Official Website](https://stability.ai/stable-diffusion)

Save the downloaded models to the appropriate directory in your project:

```bash
/path/to/your/project/models/Stable-diffusion/
```

---

## Running the Model

To run the Stable Diffusion AI model, use the following command:

```bash
python src/main.py
```

This will execute the main script that initializes the model and begins the image generation process.

---

## Contributions

Contributions are welcome! If you have suggestions or find any issues, please feel free to submit a pull request or open an issue on GitHub.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Contact

For any inquiries or support, please contact me via email at [sanand03027005@gmail.com](mailto:sanand03027005@gmail.com?subject=Enquiry%20about%20Running%20Stable%20Diffusion%20AI) or connect with me on [LinkedIn](https://www.linkedin.com/in/anands37/).

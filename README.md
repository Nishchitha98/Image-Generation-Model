# 🖼️ AI Image Generator using Stable Diffusion

Generate high-quality AI images from text prompts using **Stable Diffusion v1.5** with the Hugging Face Diffusers library.

---

## 📌 Features

- Generate images from text prompts
- Uses Stable Diffusion v1.5
- Powered by Hugging Face Diffusers
- Supports GPU acceleration
- Simple and beginner-friendly code

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Diffusers
- Transformers
- Accelerate
- Matplotlib

---

## 📦 Installation

Install the required libraries:

```bash
pip install diffusers transformers accelerate torch matplotlib
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

```bash
cd your-repository-name
```

### 2. Run the Python file

```bash
python image_generator.py
```

Enter your prompt when asked:

```
Enter your image description:
```

Example:

```
A futuristic city at sunset with flying cars
```

The generated image will be displayed automatically.

---

## ☁️ Running on Google Colab

For faster image generation, use **Google Colab**.

### Recommended Runtime

Go to:

```
Runtime → Change runtime type
```

Select:

- Hardware Accelerator: **GPU**
- GPU Type: **T4 GPU** ✅ (Recommended)

Then run all the cells.

---

## 📂 Project Structure

```
AI-Image-Generator/
│
├── image_generator.py
├── README.md
└── requirements.txt
```

---

## 📜 Code Overview

The project performs the following steps:

1. Installs required libraries
2. Loads Stable Diffusion v1.5
3. Moves the model to GPU (CUDA)
4. Accepts a text prompt from the user
5. Generates an AI image
6. Displays the generated image

---

## ⚡ Example Prompt

```
A magical forest with glowing trees under a starry night
```

---


## 🔮 Future Improvements

- Save generated images automatically
- Negative prompt support
- Image size customization
- Web interface using Gradio or Streamlit
- Multiple image generation
- Random seed support for reproducibility

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork the repository, improve the project, and submit a pull request.

---

## 📄 License

This project is intended for educational and learning purposes.

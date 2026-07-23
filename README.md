# 🖼️ AI Image Chatbot using Google Gemini

An AI-powered Image Chatbot built with Python, Google Gemini, and LangChain. The application allows users to upload a ZIP folder containing images, automatically extracts metadata, categorizes the images, and generates intelligent descriptions using Google's Gemini Pro model.

---

## 📖 About the Project

This project combines Computer Vision concepts with Generative AI to create an interactive image search assistant. Users can upload a collection of images, search them using simple keywords, and receive AI-generated descriptions along with the matching images.

The chatbot automatically processes image metadata such as filename, category, dimensions, and format, making image retrieval fast and intuitive.

---

## ✨ Features

- 📁 Upload images as a ZIP file
- 🖼️ Automatic image extraction
- 🤖 AI-generated image descriptions using Gemini Pro
- 🔍 Search images by category
- 📊 Image metadata extraction
- 📈 Database statistics
- 🖥️ Interactive chatbot interface
- 📂 Multi-image search
- 🎨 Beautiful HTML image preview
- ⚡ Fast image retrieval

---

## 🛠️ Technologies Used

- Python
- Google Gemini API
- LangChain
- Google Colab
- Pillow (PIL)
- ChromaDB
- HTML Display
- Base64 Encoding

---

## 📂 Project Workflow

```text
Upload ZIP File
        │
        ▼
Extract Images
        │
        ▼
Read Image Metadata
        │
        ▼
Categorize Images
        │
        ▼
Store Image Database
        │
        ▼
User Search Query
        │
        ▼
Gemini Generates Description
        │
        ▼
Display Matching Images
```

---

## 📦 Installation

Install the required libraries:

```bash
pip install google-generativeai==0.3.2
pip install langchain==0.1.0
pip install langchain-google-genai==0.0.6
pip install chromadb==0.4.22
pip install pillow==10.1.0
```

---

## 🚀 Usage

1. Set your Gemini API Key.
2. Run the notebook in Google Colab.
3. Upload a ZIP folder containing images.
4. Wait for the images to be processed.
5. Enter an image category such as:

```
cat
dog
lion
tiger
```

6. The chatbot displays matching images along with AI-generated descriptions.

---

## 📁 Project Structure

```text
Image-Chatbot/
│
├── Image_ChatBot.ipynb
├── images_folder/
├── README.md
└── requirements.txt
```

---

## 🤖 AI Capabilities

- Image categorization
- AI-generated descriptions
- Interactive search
- Multi-keyword search
- Image statistics
- Metadata extraction

---

## 📊 Output

- Displays matching images
- Shows image dimensions
- Shows image format
- Generates AI descriptions
- Lists available categories

---

## 🔮 Future Enhancements

- Voice Search
- OCR Support
- Face Recognition
- Object Detection
- Drag & Drop Upload
- Web Application using Streamlit
- Image Captioning
- Multi-language Support

---

## 👨‍💻 Developed By

**Nafeel Aohamed N**

- GitHub: https://github.com/NAFEEL0403

---

## 📄 License

This project is developed for educational and learning purposes.

---

⭐ If you found this project useful, don't forget to **Star** the repository!

# CSE499 Project: AUTOMATING GUI-BASED SOFTWARE TESTING WITH CHATGPT

This project generates detailed test cases for GUI-based applications by analyzing visual elements and text from images or web pages. It uses computer vision, OCR, and AI to automate the process of test case creation.

---

## Features

- **Image Processing:** Detect GUI elements using OpenCV.
- **OCR Integration:** Extract text from images using Tesseract.
- **Selenium Automation:** Interact with web pages to extract GUI elements.
- **AI-Powered Test Cases:** Use OpenAI's API to generate test cases.
- **Excel Export:** Save test cases in a structured Excel format.

---

## Prerequisites

- Python 3.9.21
- Tesseract OCR installed ([Download](https://github.com/tesseract-ocr/tesseract))
- ChromeDriver installed ([Download](https://chromedriver.chromium.org/))

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/TasinToha/cse499-project
   cd cse499-project
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set your OpenAI API key:
   - Add your API key to an environment variable named `OPENAI_API_KEY`.

---

## Usage

1. Run the application:

   ```bash
   python main.py
   ```

2. Use the GUI to:

   - Upload an image file (PNG, JPG, or JPEG).
   - Generate test cases based on the image or URL provided.

3. The generated test cases will be saved as an Excel file in the same directory as the uploaded image.

---

## Troubleshooting

- **OCR not working?**

  - Ensure Tesseract OCR is installed and its path is set correctly in the code.

- **WebDriver errors?**

  - Ensure the ChromeDriver version matches your Chrome browser version.

- **API errors?**
  - Verify your OpenAI API key is correctly set in the environment variables.

---

## License

This project is licensed under the MIT License. See `LICENSE` for more details.

---

## Contributing

Contributions are welcome! Please create a pull request or open an issue for suggestions and bug fixes.

---

## Acknowledgments

- [OpenCV](https://opencv.org/)
- [Pytesseract](https://github.com/madmaze/pytesseract)
- [Kivy](https://kivy.org/)
- [OpenAI](https://openai.com/)

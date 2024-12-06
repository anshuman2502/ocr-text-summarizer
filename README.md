# ocr-text-summarizer
This repository provides a simple and efficient OCR (Optical Character Recognition) text scanner built with Python, leveraging the power of Tesseract OCR. The project is implemented in a Jupyter Notebook and demonstrates how to extract text from images, such as scanned documents or photographs, using machine learning and image processing techniques.

### Features:
- **Image Preprocessing:** Converts images to grayscale, applies thresholding, and removes noise to improve OCR accuracy.
- **Text Extraction:** Uses Tesseract OCR to recognize and extract text from images.
- **Visualizations:** Displays processed images and extracted text within the Jupyter Notebook.
  
### Requirements:
- Python 3.x
- Libraries: 
  - `pytesseract` for OCR
  - `opencv-python` for image processing
  - `Pillow` for image handling
  - `matplotlib` for visualization
- Tesseract OCR engine installed locally (installation instructions provided in the notebook)

### Installation:
1. Clone the repository.
2. Install the necessary dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Install Tesseract OCR (instructions available in the notebook).
4. Open and run the `OCR_Scanner.ipynb` Jupyter Notebook to start extracting text from images.

### How to Use:
- Simply upload an image, run the notebook cells, and observe the results as Tesseract extracts the text from the image.

Feel free to contribute or open issues for any improvements or questions. Happy scanning!

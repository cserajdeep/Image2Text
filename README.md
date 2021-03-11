To install pytesseract: pip install pytesseract

Download tesseract installer from https://github.com/UB-Mannheim/tesseract/wiki and set the .exe path as follows:
import pytesseract
pytesseract.tesseract_cmd=r'C:\Program Files\Tesseract-OCR\tesseract.exe'  (give your installed path)

Run the following command to get the result:
$python ocr_gray_threshold.py -i medicine_strip.jpg -p blur

# Image2Text
Python code to extract text from a given image

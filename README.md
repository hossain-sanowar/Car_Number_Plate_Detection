# Car Number Plate Detection using OpenCV and EasyOCR
A machine learning project that can detect car number plate text. In this project, the number plate image is read and visualized using OpenCV and Python and then the text is extracted using EasyOCR.



# Steps which are followed
1. Using OpenCV with Python, car image is read and visualised
2. Applying color shifts and changes to images (e.g. grayscaling and BGR2RGB)
3. Using OpenCV findCountours, contours are detectd
4. Masking number plates to improve text extraction for OCR
5. Using EasyOCR, number plate text is extracted

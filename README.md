# Car Number Plate Detection using OpenCV and EasyOCR
A machine learning project that can detect car number plate text. In this project, the number plate image is read and visualized using OpenCV and Python and then the text is extracted using EasyOCR.

(N.B This is a running project for one of my masters course)

Steps which are followed
Using OpenCV with Python, car image is read and visualised
Applying color shifts and changes to images (e.g. grayscaling and BGR2RGB)
Using OpenCV findCountours, contours are detectd
Masking number plates to improve text extraction for OCR
Using EasyOCR, number plate text is extracted

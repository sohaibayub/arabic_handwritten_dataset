# arabic_handwritten_dataset

We have downloaded 6500 text files from Kaggle that belong to cultural text\footnote{\url{https://www.kaggle.com/datasets/haithemhermessi/sanad-dataset}}. Then these text files are converted to jpg images using Python library `Pillow' to generate OCR input. These images are used as input to Tesseract which gives output in text format.
# PDF-to-TEXT-Extraction-

For step 1 : (PDF to JPEG)

Download zip file with Poppler's latest binaries/dlls from 
http://blog.alivate.com.au/poppler-windows/ and unzip to a new folder in your program files folder. For example: "C:\Program Files (x86)\Poppler".

Place the location of pdftoppm.exe in pdftoppm_path .
refer : https://stackoverflow.com/questions/46184239/extract-a-page-from-a-pdf-as-a-jpeg 


For step 2 : img to text conversion 
https://stackoverflow.com/questions/57268251/text-extraction-from-multiple-image-files-using-python 

Install tesseract using windows installer available at: https://github.com/UB-Mannheim/tesseract/wiki
Set the tesseract path in the script before calling pytesseract.pytesseract.tesseract_cmd 
eg : pytesseract.pytesseract.tesseract_cmd = "C:/Program Files/Tesseract-OCR/tesseract.exe"

the above results in the program are for [all_of_statistics.pdf](https://github.com/lovishpandey/PDF-to-TEXT-Extraction-/files/7062228/all_of_statistics.pdf)


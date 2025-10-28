# Extract text from a PDF and save it to a text file.
## Aim:
To design a UiPath workflow that reads and extracts text from a scanned PDF file using Optical Character Recognition (OCR) and saves the extracted text into a text file.
       
## Procedure:

    Open UiPath Studio and create a new Process.

In the Main.xaml workflow, drag and drop the following activities in sequence:

Step 1: Read PDF With OCR

File Name: Select the PDF file (e.g., C:\Users\admin\Documents\sample.pdf).

OCR Engine: Choose Tesseract OCR.

Output: Store the result in a variable named ScannedPDFText.

Step 2: Message Box

Display the variable ScannedPDFText to verify that the text has been correctly extracted from the PDF.

Step 3: Write Text File

Specify the file path where the extracted text should be saved (e.g., C:\Users\admin\Documents\output.txt).

In the “Text” field, provide the variable ScannedPDFText.

Save and Run the workflow.

UiPath reads the scanned PDF using OCR, displays the extracted text in a message box, and then writes it into the specified text file.

<img width="1920" height="1080" alt="Screenshot (153)" src="https://github.com/user-attachments/assets/abbe0779-b5a5-4ccc-892b-b59417260e26" />
<img width="1920" height="1080" alt="Screenshot (151)" src="https://github.com/user-attachments/assets/98fa3d7d-5a42-4a53-9a53-41b270e0ab8f" />
<img width="1920" height="1080" alt="Screenshot (152)" src="https://github.com/user-attachments/assets/dbd8a9f6-5495-4ce2-bc08-a451483d8a29" />

# Result:
   The workflow successfully reads the scanned PDF document, extracts its text content using the Tesseract OCR engine, and saves the recognized text into a text file. The extracted text is also displayed in a message box for verification.




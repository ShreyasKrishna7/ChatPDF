# ChatPDF - A PDF Chatbot Using Vision Language Models
ChatPDF is a Python application that allows you to interact with a PDF document as if you were chatting with it. The program converts a PDF into an image, processes it using a Vision Language Model, and provides answers to your questions based on the content of the PDF image.

The program utilizes a pre-trained Vision Language Model hosted on Hugging Face, which is capable of performing OCR (Optical Character Recognition) on the provided image and generating responses to textual queries about the content.

# Requirements
To run this project, you need Python 3.10+ and the required dependencies installed in a virtual environment.

You can install the dependencies using the requirements.txt file provided.

# Usage
Prepare a PDF file: The program assumes that the PDF contains only one page. Ensure that the PDF you provide is relatively simple for the model to process.

Run the program:

Execute the Python script, chat_pdf.py,  to start the application.

Provide the path to your PDF: When prompted, provide the full path to the PDF file you wish to interact with.

Ask questions: Once the PDF is processed, you can ask questions about the document's content. The model will attempt to provide answers based on the image of the document.

Notes
This implementation assumes that the PDF contains only one page. If your document has more pages, modifications to the code may be needed.
The model is a pre-trained Vision Language Model, and its accuracy may vary depending on the content of the PDF.
For more accurate results, you can try fine-tuning the model with specific datasets or using more advanced prompt engineering techniques.

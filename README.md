HOME PAGE
![image](https://github.com/user-attachments/assets/5b34f31e-f359-4826-82c9-b4335804f0db)


Other Screenshots 

![WhatsApp Image 2024-10-14 at 12 46 42 PM](https://github.com/user-attachments/assets/81a5b133-6d4d-41db-b806-1d03407ce516)
![WhatsApp Image 2024-10-14 at 12 48 12 PM](https://github.com/user-attachments/assets/96c50710-e1c2-44ea-9a18-e29416e20ae3)
![WhatsApp Image 2024-10-14 at 12 49 00 PM](https://github.com/user-attachments/assets/80951006-5afd-4db5-b2b6-3e2ff373ad22)
![WhatsApp Image 2024-10-14 at 12 50 20 PM](https://github.com/user-attachments/assets/0c97eb91-c6e7-41af-909e-31cc028f2ec2)


DESCRIPTION 

This project involves developing a robust system that enables users to upload multiple PDF documents and interact with their content by submitting related queries. The system processes the uploaded PDFs by extracting and organizing their content, allowing users to ask questions based on the information contained within the documents.

Key features include:

Multiple PDF Upload: Users can securely upload multiple PDF files in a single session.
Content Extraction: The system extracts text from the PDFs, including handling scanned documents using OCR if necessary.
Query Processing: Users can submit questions based on the content of the uploaded PDFs, with the system analyzing the extracted data to provide relevant responses.
User-Friendly Interface: The interface allows easy navigation between uploaded files and question submission, ensuring a seamless user experience.


Project Setup and Usage Instructions
Follow these steps to get the project up and running on your local machine:

1. Clone the Repository
Open your terminal.
Run the following command to clone the project to your local machine:
bash

```git clone <repository-url>```
2. Configure Environment Variables
Navigate to the project directory:
bash

```cd <project-directory>```
Open the .env file located in the project folder.
Paste your Google Gemini API key in the .env file, like this:
makefile

```GOOGLE_GEMINI_API_KEY=your_api_key_here```
3. Run the Application
Open your terminal in the project directory.
Run the following command to start the application using Streamlit:
bash
Copy code
```streamlit run app.py```
4. Upload Multiple PDFs
Once the application starts, upload multiple PDF files using the provided interface.
Click on the Submit button after uploading the files.
5. Ask Questions
After submitting the PDFs, you can ask questions based on the content of the uploaded documents, and the system will provide answers accordingly.


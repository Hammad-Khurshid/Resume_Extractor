# Resume_Extractor

The Resume Parser project is a tool designed to extract key information such as skills, experience, email, and name from resumes. This parser can handle resumes in various formats including PDF and DOCX, and can also process resumes contained within ZIP files.

## Features

- **Extract Skills**: Identify and extract skills listed in the resume.
- **Extract Experience**: Identify and extract experience details.
- **Extract Email**: Identify and extract email addresses.
- **Extract Name**: Identify and extract the candidate's name.
- **Multi-format Support**: Parse resumes in PDF, DOCX, and ZIP file formats.

## Requirements Installation

pip install nltk

pip install spacy==2.3.5

pip install https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-2.3.1/en_core_web_sm-2.3.1.tar.gz

pip install pyresparser


1. **Clone the repository**

   ```bash
   git clone https://github.com/Hammad-Khurshid/Resume_Extractor.git
   cd Resume_Extractor

**Create a virtual environment**

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

**Usage**
python3 main.py or server.py
and then run index.html file to upload 

**Output**

Detect file format: Identify if the input is a PDF, DOCX, or ZIP file.
Extract text: Extract text from the identified format.
Parse information: Use regular expressions and text processing to extract skills, experience, email, and name.
Display results: Print the extracted information.
Example
Assume you have a resume in a PDF file named resume.pdf:

The output will display the extracted skills, experience, email, and name from the resume.

**Contributing**

Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

**License**

This project is licensed under the MIT License - see the LICENSE file for details.

**Contact**

If you have any questions or feedback, feel free to reach out at [hammad.khurshid175@gmail.com].

Thank you for using this resume parser. We hope it helps streamline your resume processing workflow.

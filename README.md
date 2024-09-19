# 🤖 ATS Resume Expert

![ATS Resume Expert Banner](https://github.com/yourusername/ats-resume-expert/blob/main/banner.png?raw=true)

Welcome to **ATS Resume Expert**! 🎉 This Streamlit application leverages advanced AI to help you optimize your resume for Applicant Tracking Systems (ATS) and align it perfectly with job descriptions. Whether you're looking to understand how your resume matches a job posting or seeking ways to enhance your skills, ATS Resume Expert has got you covered! 🚀

## 📋 Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🌟 Features

- **Resume Evaluation**: Get professional feedback on how well your resume aligns with a specific job description.
- **Skill Improvement Suggestions**: Receive actionable advice to enhance your skills and improve your resume.
- **Percentage Match Analysis**: Understand the percentage match between your resume and the job description, along with missing keywords.
- **User-Friendly Interface**: Intuitive and easy-to-use interface built with Streamlit.
- **Secure File Uploads**: Upload your resume securely in PDF format for analysis.

## 🚀 Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/ats-resume-expert.git
   cd ats-resume-expert

 python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

GOOGLE_API_KEY=your_google_api_key_here

🛠️ Usage
Run the Streamlit app using the following command:
streamlit run app.py

The application will open in your default web browser. Follow these steps:

Enter Job Description: Paste the job description you're targeting.
Upload Your Resume: Upload your resume in PDF format.

Choose an Action:
Tell me about the resume 📝: Get a professional evaluation of how your resume aligns with the job description.
How can I improve my skills 📈: Receive suggestions to enhance your skills and resume.
Percentage match 📊: Get a percentage match of your resume against the job description, including missing keywords.


🔧 Environment Variables
The application uses environment variables to manage sensitive information. Ensure you have a .env file with the following:
GOOGLE_API_KEY=your_google_api_key_here


📦 Dependencies
Key libraries and tools used in this project:

Streamlit 🚀: For building the web application interface.
Python-dotenv 📂: To load environment variables from a .env file.
Pillow (PIL) 🖼️: For image processing.
pdf2image 📄: To convert PDF files to images.
Google Generative AI 🤖: For generating AI-based responses.
Base64 🔐: For encoding binary data.


📫 Contact
Have questions or suggestions? Reach out to us!

Email: suprithsreekantaswamy@gmail.com
GitHub: Suprith-17

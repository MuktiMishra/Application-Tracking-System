# Application-Tracking-System
## Resume-ATS-Tracking-LLM-Project-With-Google-Gemini-Pro

## Overview
Welcome to the Gemini Pro Applicant Tracking System (ATS)! This system is developed using the powerful Gemini Pro model to streamline the hiring process by analyzing job descriptions and resumes. It provides valuable insights such as job description match, missing keywords, and profile summary.

## Features
- **Job Description Match:** The system evaluates how well a candidate's resume matches the provided job description, helping recruiters quickly identify suitable candidates.

- **Missing Keywords:** It identifies keywords or skills that are missing in the resume but are crucial for the job, enabling recruiters to guide candidates on enhancing their profiles.

- **Profile Summary:** The system generates a concise profile summary highlighting key strengths and qualifications, facilitating a quick understanding of the candidate's suitability for the position.

## Requirements
- Python 3.10
- Gemini Pro model api key (Note: Ensure you have the necessary credentials and permissions to access the Gemini Pro API)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/MuktiMishra/Application-Tracking-System.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up Gemini Pro API credentials:
 - Obtain API credentials from the makersuit platform.

 - Create a file named .env in the project root directory.

 - Add the following lines to .env:
   ```bash
   GEMINI_API_KEY= "your_api_key"
   ```

## Usage
1. Run the application:
```bash
streamlit run app.py
```
2. Access the application through your web browser at http://localhost:5000.

3. Input the job description and candidate's resume in the provided fields.

4. Click the "Submit" button to initiate the analysis.

5. Review the results, including the job description match, missing keywords, and profile summary.


## Contributing
If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and submit a pull request.


## License
This project is licensed under the MIT License.


Happy recruiting with Gemini Pro ATS!
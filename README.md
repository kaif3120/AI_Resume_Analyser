
## AI Resume Analyzer Overview

The AI Resume Analyzer is a powerful tool designed to enhance resume evaluation using advanced natural language processing (NLP) techniques. It provides insights and recommendations to both job seekers and recruiters by parsing resume data, extracting keywords, and offering actionable analytics. This tool is ideal for improving resume quality and streamlining the recruitment process.

### Key Features

- **Resume Parsing**: Extracts and structures information from resumes.
- **Keyword Analysis**: Identifies and clusters keywords to provide relevant recommendations.
- **Predictions and Recommendations**: Offers tailored suggestions for skills, courses, and certifications.
- **Analytics**: Provides detailed analytics and reports on resume data and user feedback.
- **Admin Dashboard**: Allows admins to manage data, view feedback, and export user data.

### Tech Stack

- **Frontend**: Streamlit, HTML, CSS, JavaScript
- **Backend**: Python, Streamlit
- **Database**: MySQL
- **Modules**: pandas, pyresparser, pdfminer3, Plotly, NLTK

### Setup & Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/kaif3120/AI_Resume_Analyser.git
   ```

2. **Create and Activate a Virtual Environment**:
   ```bash
   python -m venv venvapp
   cd venvapp/Scripts
   activate
   ```

3. **Install Dependencies**:
   ```bash
   cd ../..
   cd App
   pip install -r requirements.txt
   python -m spacy download en_core_web_sm
   ```

4. **Create a Database**:
   - Create a MySQL database named `cv`.

5. **Configure User Credentials**:
   - Update user credentials in `App.py` as per the provided instructions in the repository.

6. **Replace File in `pyresparser`**:
   - Replace `resume_parser.py` in the `venvapp\Lib\site-packages\pyresparser` directory with the provided version.

7. **Run the Application**:
   ```bash
   streamlit run App.py
   ```

### Admin Credentials

- **Username**: `admin`
- **Password**: `admin@resume-analyzer`

### Known Issues

- **GeocoderUnavailable Error**: Check your internet connection if this error occurs.

For more details, installation help, or to request the full project report, please feel free to [email me](mailto:shaikhkaif3120@gmail.com).
"# AI_Resume_Analyser" 

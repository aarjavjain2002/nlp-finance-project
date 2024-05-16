## Setting Up the Environment

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   
   cd <repository-directory>
   
   python3 -m venv venv
   
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   
   pip install -r requirements.txt
   
   python -m spacy download en_core_web_sm

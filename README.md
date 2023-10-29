# Cover Letter Generator

Introducing the Cover Letter Generator, a cutting-edge tool crafted to help you craft an impeccable cover letter for your ideal job. It combines the capabilities of Streamlit and OpenAI to deliver a customized and polished cover letter that suits your specific requirements.

![demo](demos/demo.gif)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/codemaker2015/cover-letter-generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd cover-letter-generator
   ```

3. Install the dependencies:

   ```python
   pip install -r requirements.txt
   ```

4. Paste your Replicate API token in the secrets.toml file:

   ```bash
   OPENAI_API_KEY = "paste-your-openai-key"
   ```

## Dependencies

- OpenAI
- Streamlit
- PyPDF2

## Usage

1. Run the Streamlit app:

   ```python
   streamlit run app.py
   ```

2. Navigate to the provided local URL, and start crafting your covering beautiful letter.

3. Fill the information such as: 
    - Your name
    - Company name
    - Hiring manager's name
    - Upload your resume
    - Paste the job description
4. Click the "Generate Cover Letter" button.

5. Review and customize the generated cover letter if necessary.

6. Click the "Download" button to save the generated covering letter as a text file.
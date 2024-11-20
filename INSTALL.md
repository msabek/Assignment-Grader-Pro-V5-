# Installation Guide for Assignment Grader Pro

## System Requirements
- Windows 10 or later
- Python 3.8 or later
- Internet connection for AI model access

## Installation Steps

1. **Install Python**
   - Download Python from [python.org](https://www.python.org/downloads/)
   - During installation, make sure to check "Add Python to PATH"
   - Verify installation by opening Command Prompt and typing:
     ```
     python --version
     ```

2. **Download Assignment Grader Pro**
   - Extract the downloaded zip file to your preferred location

3. **Configure API Keys**
   - Create a `.env` file in the application directory
   - Add your API keys in the following format:
     ```
     OPENAI_API_KEY=your_openai_key_here
     GROQ_API_KEY=your_groq_key_here
     MISTRAL_API_KEY=your_mistral_key_here
     ```

4. **Launch the Application**
   - Double-click `run_grader.bat`
   - The script will automatically:
     - Install required dependencies
     - Start the application
     - Open your default web browser

5. **First-Time Setup**
   - When the application starts, it will open in your default web browser
   - Configure your preferred AI model in the sidebar
   - Set up your marking criteria
   - You're ready to start grading!

## Troubleshooting

If you encounter any issues:

1. **Python not found**
   - Make sure Python is installed and added to PATH
   - Try restarting your computer after installation

2. **Dependencies installation fails**
   - Run Command Prompt as Administrator
   - Try running:
     ```
     pip install --upgrade pip
     pip install -r requirements.txt
     ```

3. **Application won't start**
   - Check if port 8501 is available
   - Make sure all API keys are correctly configured
   - Check your internet connection

For additional help, refer to the USER_GUIDE.md or contact support.

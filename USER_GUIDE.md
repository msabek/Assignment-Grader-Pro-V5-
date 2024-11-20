# Assignment Grader Pro - User Guide

## Overview
Assignment Grader Pro is a powerful tool designed to assist educators and teaching assistants in grading assignments using AI-powered text comparison. The application supports multiple AI providers and offers comprehensive grading features with statistical analysis capabilities.

## Getting Started

### Prerequisites
- Python environment with the required dependencies (listed in `requirements.txt`)
- API keys for the AI services you plan to use (OpenAI, Groq, Mistral, etc.)
- Access to Ollama if you plan to use local models

### Installation
1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

2. Set up your environment variables or configure API keys through the application interface

### Running the Application
Launch the application using Streamlit:
```bash
streamlit run main.py
```

## Features

### 1. Evaluation Settings
Located in the sidebar, this section allows you to:
- Select your preferred AI model provider
- Configure API keys
- Set model parameters (temperature, max tokens)
- Define marking criteria

### 2. File Processing
The application supports:
- Upload of student submissions
- Processing of multiple file formats
- Batch processing capabilities

### 3. Grading Process
1. **Upload Files**: Submit student assignments through the file upload interface
2. **Configure Criteria**: Set or modify the marking criteria
3. **Run Analysis**: The system will analyze submissions using the selected AI model
4. **Review Results**: View detailed feedback and scores for each submission

### 4. Statistical Analysis
Access comprehensive statistical insights including:
- Score distribution
- Performance metrics
- Box plots and other visualizations
- Grade bands analysis

### 5. Report Generation
Generate detailed reports containing:
- Individual student feedback
- Scores and evaluations
- Statistical summaries
- Export capabilities for further processing

## Supported AI Providers
- OpenAI (GPT models)
- Groq
- Mistral AI
- Ollama (local models)
- OpenAI-compatible endpoints

## Best Practices
1. **Marking Criteria**: Define clear and specific marking criteria for consistent grading
2. **Model Selection**: Choose appropriate models based on your grading needs
3. **Regular Backups**: Save generated reports and maintain backups of important data
4. **Review Process**: Always review AI-generated feedback before finalizing grades

## Troubleshooting
- Ensure all API keys are correctly configured
- Check internet connectivity for cloud-based models
- Verify file formats match supported types
- Monitor token limits when processing large batches

## Support
For technical support or feature requests, please refer to the project repository or contact your system administrator.

## Security Notes
- Never share your API keys
- Regularly rotate API keys for security
- Ensure student data is handled according to your institution's privacy policies

---

This guide provides a basic overview of Assignment Grader Pro. For more detailed information about specific features or technical details, please refer to the technical documentation or contact the development team.

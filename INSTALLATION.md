# Installation Prerequisites

Before you begin setting up the AI Voice Lead Generation Automation tool, ensure you have the following prerequisites installed:

1. **Python 3.7 or higher**: Make sure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).
2. **Pip**: This package manager for Python is usually included with Python installations. You can check if it’s installed by running `pip --version` in your terminal.
3. **Git**: Ensure Git is installed on your system. Download it from [git-scm.com](https://git-scm.com/downloads).
4. **Virtualenv**: It is highly recommended to create a virtual environment for your Python projects. To install it, run `pip install virtualenv`.
   
# Step-by-step Setup Instructions

Follow these steps to set up the AI Voice Lead Generation Automation tool:

1. **Clone the Repository**: Run the following command in your terminal:
   
   ```bash
   git clone https://github.com/layaniaa/ai-voice-leadgen-automation.git
   cd ai-voice-leadgen-automation
   ```
   
2. **Create a Virtual Environment**: 
   
   ```bash
   virtualenv venv
   ``` 
   
3. **Activate the Virtual Environment**:
   - On Windows:  
   ```bash
   venv\Scripts\activate
   ``` 
   - On macOS and Linux:  
   ```bash
   source venv/bin/activate
   ``` 

4. **Install Dependencies**: Run the following command to install the required Python packages:
   
   ```bash
   pip install -r requirements.txt
   ``` 
   
5. **Configure the Application**: Follow the instructions in the `CONFIGURATION.md` file to set up your configuration settings.

6. **Run the Application**:
   
   ```bash
   python app.py
   ``` 

7. **Verify Installation**: Ensure everything was installed correctly by checking the application status.

If you encounter any issues, please refer to the Troubleshooting section in the documentation.
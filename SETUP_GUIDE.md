# Setup Guide for Voice Automation System

## Prerequisites
- Ensure you have Python 3.7 or above installed.
- Install Git for version control.
- Basic knowledge of command line interface.

## Step-by-Step Instructions

### Step 1: Clone the Repository
Run the following command in your terminal:
```bash
git clone https://github.com/layaniaa/ai-voice-leadgen-automation.git
```

### Step 2: Navigate to the Project Directory
Change your working directory to the cloned repository:
```bash
cd ai-voice-leadgen-automation
```

### Step 3: Create a Virtual Environment
It’s a good practice to create a virtual environment for Python projects. Run:
```bash
python -m venv venv
```

### Step 4: Activate the Virtual Environment
- On Windows:
```bash
venv\Scripts\activate
```
- On macOS/Linux:
```bash
source venv/bin/activate
```

### Step 5: Install Dependencies
Make sure to install the required packages:
```bash
pip install -r requirements.txt
```

### Step 6: Configure the Environment Variables
Create a `.env` file in the root directory and add the necessary environment variables. Refer to the `.env.example` for guidance.

### Step 7: Run the Application
Finally, start the application with:
```bash
python app.py
```

### Troubleshooting
If you encounter any issues, check the following:
- Validate your Python version.
- Ensure all dependencies are installed as specified in `requirements.txt`.
- Review the console output for error messages and stack traces.

## Conclusion
You should now have the voice automation system up and running! Feel free to explore the features and contribute to the project.
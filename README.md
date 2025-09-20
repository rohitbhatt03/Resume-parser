Resume Parser

A GPT-powered Resume Parser served as a REST API. It converts resume PDFs (e.g., example resume
) into structured JSON files

⏱️ Parsing time: ~15 seconds per resume
📈 Fine-tuning may improve results, but the default setup is already effective

Quick Start
### Upgrade pip
python3 -m pip install --upgrade pip

### Clone this repository and navigate to the project root
git clone https://github.com/yourusername/resume-parser-service.git
cd resume-parser-service

### Check versions
python3 --version
pip3 --version

### Build the project
./build.sh

### Set your OpenAI API Key

Get your key from OpenAI
.

Option A: Create a .env file:

OPENAI_API_KEY=YOURKEY


Option B: Export it directly:

export OPENAI_API_KEY=YOURKEY

### Run the Flask server
./run.sh

### Supported Fields
- Basic Information
  - First name / Last name / Full name
  - Email
  - Phone number
  - Location
  - Portfolio website
  - LinkedIn URL
  - GitHub profile

- Education
 - University
 - Degree / Education level
 - Graduation year & month
 - Majors
 - GPA
 
- Work Experience
 - Job title
 - Company
 - Location
 - Duration
 - Job description
 - Projects
 - Project name
 -Project description
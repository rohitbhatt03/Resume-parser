# 📄 Resume Parser  

A **GPT-powered Resume Parser** served as a **REST API**. It converts resume PDFs (e.g., example resumes) into structured JSON files.  

⏱️ **Parsing time:** ~15 seconds per resume  
📈 **Fine-tuning** may improve results, but the default setup is already effective.  

---

## 🚀 Quick Start  

### 1️⃣ Upgrade pip  
python3 -m pip install --upgrade pip

### 2️⃣ Clone this repository
git clone https://github.com/rohitbhatt03/Resume-parser.git

cd Resume-parser

### 3️⃣ Check versions
python3 --version
pip3 --version

### 4️⃣ Build the project
./build.sh

### 5️⃣ Set your OpenAI API Key
Get your API key from OpenAI

- Option A: Create a .env file
  - OPENAI_API_KEY=YOURKEY
- Option B: Export it directly
  - export OPENAI_API_KEY=YOURKEY

### 6️⃣ Run the Flask server
./run.sh

### 🧾 Supported Fields
### 👤 Basic Information
  - First name / Last name / Full name
  - Email
  - Phone number
  - Location
  - Portfolio website
  - LinkedIn URL
  - GitHub profile
### 🎓 Education
  - University
  - Degree / Education level
  - Graduation year & month
  - Majors
  - GPA
### 💼 Work Experience
  - Job title
  - Company
  - Location
  - Duration
  - Job description
### 🛠️ Projects
  - Project name
  - Project description

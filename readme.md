# Create a new project folder
mkdir <project_folder_name>

# Move into the project folder
cd <project_folder_name>

# Open the folder in VS Code
code .

# Create a new Conda environment with Python 3.10
conda create -p document_portal python=3.10 -y

# Activate the environment (use full path to the environment)
conda activate C:\d_drive\GenAICoding\document_portal\document_portal

# Install dependencies from requirements.txt
pip install -r requirements.txt

# Initialize Git
git init

# Stage all files
git add .

# Commit changes
git commit -m "<write your commit message>"


# Push to remote (after adding remote origin)
git push

# Cloning the repository
git clone https://github.com/GOURAVRISHI/doc_portal.git



conda create -p doc_portal_new python=3.10 -y
conda activate C:\d_drive\GenAICoding\doc_portal1\doc_portal_new

pip install -r requirements.txt

git commit -m "updating folder structure"

# Minimum Requirements for the Project
## LLM Models
- Groq (Free)
- OpenAI (Paid)
- Gemini (15 Days Free Access)
- Claude (Paid)
- Hugging Face (Free)
- Ollama (Local Setup)

## Embedding Models
- OpenAI
- Hugging Face
- Gemini

## Vector Databases
- In-Memory
- On-Disk
- Cloud-Based

# API Keys
## GROQ API Key

## Gemini API Key

updating gitignore file

conda deactivate C:\d_drive\GenAICoding\doc_portal1\doc_portal


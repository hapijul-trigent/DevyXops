# **🚀 AI-Powered DevOps Automation (GitHub Actions + CrewAI)**
This project automates **CI/CD pipeline monitoring, error detection, and deployment management** using **CrewAI** and **GitHub Actions API**. It employs **AI-powered agents** to track workflow executions, detect failures, and decide rollback or deployment actions.

---

## **📌 Features**
✅ **CI/CD Monitoring Agent** – Tracks GitHub Actions workflows & detects failures  
✅ **Error Detection Agent** – Analyzes logs & suggests fixes using AI  
✅ **Deployment Agent** – Handles automatic deployments & rollback on failures  
✅ **CrewAI Integration** – Enables agent collaboration for intelligent decision-making  
✅ **Modular Design (SOLID Principles)** – Easy to maintain, extend, and scale  

---

## **📁 Project Structure**
```
ai_devops_poc/
│── main.py                # Entry point of the application
│── agents/
│   ├── ci_cd_monitor.py   # CI/CD Monitoring Agent
│   ├── deployment.py      # Deployment Agent
│   ├── error_detection.py # Error Detection Agent
│── services/
│   ├── github_api.py      # GitHub API interactions
│── crew_manager.py        # CrewAI manager handling agent execution
│── config.py              # Configuration variables
│── README.md              # Project Documentation
```

---

## **🛠️ Setup & Installation**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/ai-devops-poc.git
cd ai-devops-poc
```

### **2️⃣ Set Up a Virtual Environment**
```bash
python -m venv devops-env
source devops-env/bin/activate  # (Linux/macOS)
devops-env\Scripts\activate  # (Windows)
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

> **🔹 `requirements.txt`**
```txt
crewai
requests
```

### **4️⃣ Configure GitHub API Credentials**
Edit `config.py` and set your **GitHub repository details & token**:
```python
GITHUB_OWNER = "your_github_org_or_username"
GITHUB_REPO = "your_repo_name"
GITHUB_TOKEN = "your_github_personal_access_token"
```

---

## **🚀 How to Run the Project**
Start monitoring the GitHub Actions workflow:
```bash
python main.py
```

> ✅ **The AI-powered agents will:**
> - Track CI/CD pipeline execution in **real-time**
> - **Analyze failures** and suggest **fixes**
> - **Rollback failed deployments** automatically

---

## **🔍 How It Works**
### **1️⃣ CI/CD Monitoring Agent**
- **Monitors** GitHub Actions workflow runs
- Detects **failures** and logs execution status

### **2️⃣ Error Detection Agent**
- Fetches **workflow logs** from GitHub
- Analyzes errors using **AI-driven log processing**
- Suggests **possible fixes**

### **3️⃣ Deployment Agent**
- Deploys successful builds
- **Automatically rolls back** failed releases
- Ensures **zero-downtime deployment strategies**

---

## **🛠️ Future Scope**
Want to enhance AI-powered automation?  
🚀 **Add More Agents!**
- **Security Agent** → Scan deployments for vulnerabilities  
- **Performance Optimization Agent** → Monitor build times & optimize CI/CD steps  
- **Self-Healing Agent** → Auto-fix errors using past failure patterns  

---

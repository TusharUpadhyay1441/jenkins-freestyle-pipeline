# Jenkins Freestyle Delivery Pipeline

This project demonstrates how to build a delivery pipeline using **Jenkins Freestyle Jobs** with upstream and downstream triggers.  

---

## 🚀 Pipeline Overview
The pipeline consists of 4 stages, implemented as separate Freestyle jobs:

1. **Compile** – Compiles the source code.  
2. **Code Review** – Runs static analysis or linting checks.  
3. **Test** – Executes unit/integration tests.  
4. **Package** – Packages the build artifacts.  

Jobs are connected using **upstream and downstream triggers**, so the pipeline executes in sequence.

---

## 🔧 Tools & Technologies
- **Jenkins Freestyle Jobs**
- Upstream/Downstream Triggers
- GitHub Integration
- Maven (for build) / Any build tool

---

## 📸 Screenshots
(Add screenshots here to showcase Jenkins job configuration & pipeline view)

Example:
- `images/job-compile.png`
- `images/job-code-review.png`
- `images/job-test.png`
- `images/job-package.png`
- `images/pipeline-view.png`

---
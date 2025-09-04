# Jenkins Freestyle Delivery Pipeline

This project demonstrates how to build a delivery pipeline using **Jenkins Freestyle Jobs** with upstream and downstream triggers.  

---

## 🚀 Pipeline Overview
The pipeline consists of 4 stages, implemented as separate Freestyle jobs:

1. **Compile** – Compiles the source code.  
2. **Code Review** – Runs static analysis or linting checks using **PDM Warning**.  
3. **Test** – Executes unit/integration tests using **JUnit Test Result Report**.  
4. **Package** – Packages the build artifacts.  

Jobs are connected using **upstream and downstream triggers**, so the pipeline executes in sequence.

---

## 🔧 Tools & Technologies
- **Jenkins Freestyle Jobs**
- Upstream/Downstream Triggers
- GitHub Integration
- Maven (for build)

---

## 📸 Screenshots

## Code Complie
- <img src="images/Compile.png">
-------------------------------------
## Code Review
- <img src="images/Review.png"> <img src="images/Review PDM.png">
-------------------------------------
## Code Test
- <img src="images/test.png"> <img src="images/test result.png">
-------------------------------------
## Code Package
- <img src="images/Package.png">
-------------------------------------
## Pipeline View
- <img src="images/Pipeline View.png"> 
-------------------------------------
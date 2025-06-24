# AI-Powered-ATS-Optimized-Resume-and-Cover-Letter-Generator

## 💡 Overview

This project is an AI-powered tool designed to help job seekers generate **ATS-friendly, highly tailored resumes and cover letters** based on specific job applications. It leverages **GPT-4o**, the latest generation of OpenAI's language model, to analyze job descriptions and optimize resume content automatically. The output is a professionally formatted **LaTeX-based PDF resume and cover letter**, ready for submission.

The tool aims to solve a common problem faced by job seekers: **generic resumes and cover letters often get rejected by Applicant Tracking Systems (ATS)** or hiring managers due to lack of alignment with the job description. By dynamically tailoring these documents for each application, this tool significantly boosts the chances of getting noticed.

---

## ⚙️ Features

✅ Generates **ATS-friendly** and highly relevant resumes.  
✅ Auto-creates customized **cover letters** based on the job details.  
✅ Uses **GPT-4o** to analyze job descriptions and your existing projects/skills.  
✅ Selects the **most relevant 4 projects** from a predefined set of 7 projects.  
✅ Dynamically updates key resume sections:
- Executive Summary  
- Internship Experience  
- Projects  
- Skills  

✅ Professionally formatted output using **LaTeX templates**.  
✅ Saves time by automating repetitive resume tailoring.  
✅ Ideal for applying through job portals where ATS systems are used.  

---

## 🏗️ Project Workflow

The tool operates through the following steps:

### 1️⃣ **User Inputs**
The user provides four essential inputs:
- **Job Title**
- **Job Description**
- **Company Name**
- **Location**

---

### 2️⃣ **Predefined Resources**
- **8 projects** saved in a structured JSON file.
- Predefined **LaTeX templates** for the resume and cover letter.

---

### 3️⃣ **GPT-4o Driven Process**

The tool uses three separate GPT-powered functions:

#### 🔹 `select_best_projects()`
- Analyzes the job description and selects the **4 most relevant projects** from your predefined list.
- These projects are integrated into the LaTeX resume template.

#### 🔹 `prompt_gpt4o()`
- Analyzes:
  - The job description, title, company, and location.
  - The current LaTeX resume (with the 4 selected projects).
- Reshapes and rewrites the following resume sections to align with the job description:
  - Executive Summary  
  - Internship Experience  
  - Projects  
  - Skills  

#### 🔹 `generate_cover_letter_body()`
- Generates a **personalized cover letter** using the provided inputs.
- The content is formatted using the LaTeX template for a clean, professional look.

---

### 4️⃣ **Final Output**
- A fully customized **ATS-friendly Resume (PDF)**.  
- A tailored **Cover Letter (PDF)**.  

Both documents are ready for immediate submission through job portals.

---

## 📦 Technologies Used

- **Python** (Jupyter Notebook based implementation)  
- **OpenAI GPT-4o** API  
- **LaTeX** for professional document formatting  
- **JSON** for storing predefined project details  
- **Streamlit** *(Optional, can be integrated for building a user-friendly UI in the future)*  

---

## 🎯 Why This Project Matters

- Most resumes fail ATS filters due to poor alignment with job requirements.  
- Manually tailoring resumes for every job is time-consuming.  
- This AI tool automates the process, ensuring every application is optimized.  
- Increases chances of interview shortlisting and recruiter attention.  

---


---

## 🚀 Future Improvements

- Building a **Streamlit Web App** for non-technical users.  
- Adding more advanced AI logic for project and skill selection.  
- Incorporating additional sections like Certifications or Awards.  
- Adding support for multiple resume formats (Word, HTML).  

---

## 📄 License

This project is for educational and personal use. Commercial use may require modification or compliance with OpenAI API terms.

---

## 🤝 Acknowledgements

- **OpenAI GPT-4o** for the powerful AI model.  
- Inspiration from real-world job search challenges.  
- LaTeX community for professional document formatting tools.  

---

## 📬 Contact

If you have suggestions or would like to collaborate, feel free to reach out!


Name: [Mohamed Sahad M]
Email: [mohamedsahadm786@gmail.com]
LinkedIn: [https://www.linkedin.com/in/mohamed-sahad-m-96b038200/]



---





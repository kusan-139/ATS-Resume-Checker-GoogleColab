**Project Title:** ATS Resume \& Job Description Analyzer



**Problem Solved:**



In today's competitive job market, many companies use ATS software to filter resumes based on keywords and relevance to the job description. This tool helps candidates understand how well their resume aligns with a target job post, identifying strengths and areas for improvement to increase their chances of passing initial ATS screenings.



Key Features:



PDF Job Description Input: Easily upload job descriptions in PDF format.



Intelligent Job Information Extraction: Leverages the Google Gemini API to extract crucial details from the job description, including:



* Job Title, Company, Location
* 
* Required and Preferred Skills
* 
* Experience Level
* 
* Key Responsibilities and Qualifications



**PDF Resume Input:** 



Upload your resume directly as a PDF for analysis.



**ATS Compatibility Score:** 



Calculates an "ATS Score" (out of 100) indicating how well your resume matches the job requirements.



**Keyword Analysis:** 



Identifies and lists keywords from the job description that are present in your resume, as well as those that are missing.



**Detailed Explanation:** 



Provides a comprehensive explanation for the ATS score, highlighting the resume's strengths and weaknesses specific to the job post.



**Downloadable PDF Report:** 



Generates a well-structured PDF report summarizing the entire analysis, including extracted job info, ATS score, keyword breakdown, and explanation, for easy review and sharing.



**Technologies Used:**



**Python:** The core programming language.



**Google Colaboratory:** The development environment for easy execution and sharing.



**PyPDF2:** For extracting text content from PDF files.



**Requests:** For making HTTP requests to the Google Gemini API.



**ReportLab:** For professional and robust PDF report generation.



**Google Gemini API:** A large language model used for intelligent job description parsing and resume-to-job description comparison.



***How to Use:***



**Clone/Open in Colab:** Open the .ipynb notebook directly in Google Colab (click the "Open in Colab" badge in the README).



**Install Dependencies:** Run the first cell to install PyPDF2, requests, and reportlab.



**Provide API Key:** Obtain a Google Gemini API key from Google AI Studio and paste it into the designated API\_KEY variable in the code.



**Run the Notebook:** Execute the main code cell.



**Upload PDFs:** Follow the prompts to upload your Job Description PDF and then your Resume PDF.



**View Analysis \& Download Report:** The analysis will be displayed in the Colab output, and a detailed PDF report will be automatically downloaded to your local machine.


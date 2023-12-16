#Project is created just an attempt to learn and implement natural language processing

Project Name: Resume Matcher

Description:
1. The Resume Matcher project is a simple yet powerful tool designed to assist job seekers, recruiters and hiring managers in the process of candidate screening.
 
2. It helps evaluate how closely a candidate's resume aligns with a given job description by calculating a match percentage based on the textual content of both the job description
and the uploaded resume.

Key Features:

1. User-Friendly GUI: The project provides a user-friendly graphical user interface (GUI) that allows users to interact with the tool easily.

2. Input Job Description: Users can enter the job description into an input box provided in the GUI. This job description serves as the benchmark against which resumes are evaluated.

3. Upload Resumes: Users can upload resumes in DOCX (Word) format using the "Upload the Resume" button. The tool supports the evaluation of multiple resumes.

4. Match Percentage Calculation: The project calculates a match percentage between the job description and each uploaded resume. It employs the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization technique and cosine similarity to perform this calculation.

5. Result Display: The calculated match percentage for each resume is displayed in the GUI, helping recruiters quickly identify suitable candidates.

6. Stopword Removal: The project removes common English stopwords from both the job description and the resumes before performing the match calculation to focus on relevant content.


How it Works:

1. The user enters the job description into the provided input box.

2. The user uploads one or more resumes in DOCX format using the "Upload the Resume" button.

3. For each uploaded resume, the project calculates the match percentage by comparing its content with the provided job description.

4. The calculated match percentage is displayed in the GUI, allowing the user to assess the suitability of each candidate.


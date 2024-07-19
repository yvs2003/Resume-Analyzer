## Source
- Extracting user's information from the Resume, I used [PyResparser]
- Extracting Resume PDF into Text, I used [PDFMiner]

## Features
- User's & Admin Section
- Resume Score
- Career Recommendations
- Resume writing Tips suggestions
- Courses Recommendations
- Skills Recommendations
- Youtube video recommendations

## Usage

  pip install -r requirements.txt
  ```
- `App.py` is the main Python file of Streamlit Web-Application. 
- `Courses.py` is the Python file that contains courses and youtube video links.
- Download XAMP or any other control panel, and turn on the Apache & SQL service.
- To run app, write following command in CMD. or use any IDE.
  ```
  streamlit run App.py
  ```
- `Uploaded_Resumes` folder is contaning the user's uploaded resumes.


Features:
PDF Text Extraction:

Extracts text content from PDF resumes, allowing for easy analysis and processing.
Skills Extraction:

Utilizes advanced NLP techniques to extract skills mentioned in the resume.


Recommend Courses:

Recommends relevant online courses or learning resources based on the skills extracted from the resume. This feature aims to assist job seekers in further developing their skills and staying competitive in their field.



TF-IDF Analysis:

Performs TF-IDF analysis to identify the importance of each term within the resume. This analysis helps in understanding the relevance and significance of different keywords and phrases.
SpaCy Models:

Utilizes spaCy, an open-source natural language processing library, to perform advanced text processing tasks such as part-of-speech tagging, entity recognition, and dependency parsing. These models enhance the accuracy and efficiency of the resume analysis process.



Usage:

Upload Resume:
Upload your resume in PDF format to initiate the analysis process.

View Extracted Skills:
Once the analysis is complete, view the list of skills extracted from your resume.


Explore Recommended Courses:
Explore the recommended online courses or learning resources tailored to your skill set. These courses can help you enhance your existing skills or acquire new ones relevant to your career goals.


TF-IDF Analysis:
Gain insights into the importance and relevance of different terms within your resume through TF-IDF analysis.



Enhance Your Resume:
Use the insights and recommendations provided by the Resume Analyzer to enhance your resume, optimize your skill set, and increase your chances of success in the job market.




Technologies Used:
Python
TensorFlow
spaCy
scikit-learn
PDFMiner
Streamlit
Getting Started:
To get started with the Resume Analyzer:

Clone the repository to your local machine.
Install the necessary dependencies using pip install -r requirements.txt.
Run the application using streamlit run App.py.
Upload your resume and explore the analysis results.



Contributions:
Contributions to the Resume Analyzer project are welcome! Whether you're interested in adding new features, improving existing functionality, or fixing bugs, your contributions are highly appreciated. Fork the repository, make your changes, and submit a pull request for review.



Contact:
For any inquiries or suggestions regarding the Resume Analyzer, feel free to contact savla.priyanshu.m@gmail.com.

Authors:
Hem Vyas
Priyanshu Savla
Vatsal Vadher
Kartik Solanki
Yagnesh Sarvaiya



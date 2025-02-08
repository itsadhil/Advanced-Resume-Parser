# Advanced-Resume-Parser
An AI-powered tool that accurately extracts key information from resumes, including personal details, work experience, education, and skills. Supports multiple formats (PDF, DOCX, TXT) and handles diverse layouts with high accuracy.

## **Key Features:**

**Resume Parsing:** Automatically extracts key information from resumes in various formats including PDF, DOCX, and HTML.

**Job Title Standardization:** Utilizes the O-NET database to standardize job titles and occupations for consistent taxonomy.

**Skill Extraction:** Mines detailed skills from project descriptions using advanced Natural Language Processing (NLP) techniques.

**Resume Section Identification:** Uses Named Entity Recognition (NER) to accurately identify and classify resume sections such as experience, education, skills, and more.

### **Who It's For:**

**HR Professionals:**
 Simplifies the screening process by providing accurate and standardized information about candidates.

**Recruiters:** Enables quick and efficient evaluation of candidate profiles, saving time and effort.

**Hiring Managers:** Facilitates better decision-making by presenting detailed insights into candidate skills and experiences.

## Screenshots

### **Text Extraction**

![Resume Text Extraction](https://i.ibb.co/yF32k00s/text-extraction.png)

### **Resume Section**

![Resume Text Extraction](https://i.ibb.co/q3XH3zMj/resume-section.png)

### **Find Job Title**

![Resume Text Extraction](https://i.ibb.co/s9PzdS5h/jobtitle.png)

### **Find ONET-Occupation**

![Resume Text Extraction](https://i.ibb.co/0yNjpHFv/onet-occupation.png)

### **Extract Skills from Porject Description**

![Resume Text Extraction](https://i.ibb.co/zW4KLCJh/skills-proj-desp.png)

## Installation

Install ResumeRevealer with python >= 3.9

> Tested on python 3.11

```bash
  git clone https://github.com/itsadhil/Advanced-Resume-Parser.git
  cd Advanced-Resume-Parser
```

Install the requirements.

```bash
  pip install -r requirements.txt
```


# Model Download:

Downloaad the Model And paste in JDModel Folder: https://drive.google.com/file/d/1Dr0TYscta9oXMwLiRCZ4bZunPYQXyeHt/view?usp=sharing
> save it in a :
> ```models/ner/JdModel```

### *Run*

```toolkit.ipynb```

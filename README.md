## Job Description Data Analysis and Automation

In this project, we will explore and analyze job description data by leveraging web scraping techniques and advanced data processing tools. The goal is to collect job descriptions from Google Jobs, clean and process the data, and extract meaningful insights for better understanding of job trends across various industries.

### Part 1: Job Description Crawling

The first step involves using the serpapi API to crawl Google Jobs. This API allows for efficient and scalable searching of Google job listings. We'll collect job descriptions from a variety of roles across different sectors, industries, and locations. The API has a free tier which will suffice for this project.

### Part 2: Data Cleaning and Feature Extraction

Once the job descriptions are crawled, we will manually clean and preprocess the data. The objective is to extract as many relevant features as possible for later analysis, such as:

- **Job Title**
- **Company Name**
- **Sector/Industry**
- **Location**
- **Job Type**
- **Salary**
- **Experience Level**
- **Education Requirements**
- **Skills/Technologies Required**
- **Job Responsibilities**
- **Company Size and Reputation**
- **Remote Work Options**
- **Application Deadline**

The cleaned data will be stored in a CSV file (`data/processed-jobs-1.csv`) for exploratory data analysis (EDA).

### Part 3: Leveraging LLM APIs for Cleaning (Part-2)

In the next phase, we'll refine our cleaning process using Large Language Models (LLMs) to automate and streamline the extraction of key information from job descriptions. Various APIs, such as OpenAI and others, will be used to enhance data processing efficiency through prompt engineering.

### Part 4: Exploratory Data Analysis (EDA)

We'll perform visual exploratory data analysis on the cleaned dataset to uncover trends, patterns, and relationships. Key analyses will include:

- **Univariate Analysis**: Distribution of job titles, salary ranges, and job types.
- **Bivariate Analysis**: Relationships between salary and experience level, job type, and location.
- **Text Analysis**: Keyword frequency, sentiment analysis, and NLP-based clustering of job titles.
- **Geospatial Analysis**: Visualization of job locations and salary distribution across regions.

### Part 5: Resume and Cover Letter Automation

Building on the previous work, we'll create a pipeline using an LLM API and Quarto to generate personalized resumes and cover letters for each job description. The final output will be a PDF or HTML resume and cover letter tailored to the job posting.

### Tools and Technologies

- **serpapi API**: Web scraping of Google Jobs.
- **Pandas**: Data cleaning and manipulation.
- **Matplotlib, Seaborn**: Data visualization.
- **Folium**: Geo-spatial analysis.
- **OpenAI API or similar**: Large Language Models for text processing.
- **Quarto**: Document generation for resumes and cover letters.


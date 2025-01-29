Project Overview:
In this project, I developed a data pipeline to automate the retrieval and processing of survey responses from SurveyMonkey. Using Python, I integrated with the SurveyMonkey API to fetch survey metadata and response data, transforming it into a structured format suitable for analysis and reporting.
Key Features & Techniques Used:

•	API Integration with SurveyMonkey:
  o	Utilized Python's requests library to interact with the SurveyMonkey API, securely accessing survey data using an API token.
•	Dynamic Data Extraction:
  o	Extracted survey questions, answer choices, and responses dynamically, ensuring that all data points are captured accurately.
•	Data Transformation:
  o	Mapped question IDs to human-readable text for easier interpretation.
  o	Converted complex JSON response structures into a tidy Pandas DataFrame for analysis.
•	Automation of Data Export:
  o	Exported processed survey responses to Excel for further analysis, making the data easily accessible for stakeholders.

Workflow:
  1.	API Authentication:
    o	Configured API access using secure tokens to ensure authorized data retrieval.

2.	Data Retrieval:
  o	Fetched survey details and responses, handling pagination to capture large datasets efficiently.

3.	Data Processing:
  o	Transformed response data into structured tables, mapping question IDs to meaningful text.

4.	Export & Reporting:
  o	Saved the processed data into Excel files for easy sharing and visualization.

Use Cases:
•	Automating survey response collection for ongoing feedback.
•	Simplifying data analysis by transforming API data into readable formats.
•	Enhancing reporting capabilities for health monitoring and infection control.
Technology Stack:
•	Programming Language: Python
•	Libraries: Pandas, Requests
•	Data Source: SurveyMonkey API
•	Output: Excel Report
Challenges & Solutions:
•	Handling Complex JSON Structures:
  o	Implemented recursive data extraction techniques to handle nested JSON data.
•	Ensuring Data Accuracy:
  o	Validated API responses and handled errors gracefully to ensure reliable data extraction.
Future Improvements:
•	Automate the pipeline with scheduled scripts or cloud-based workflows.
•	Integrate with data visualization tools like Power BI or Tableau for enhanced insights.

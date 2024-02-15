# TSA Insurance Claims Analysis

## General Guidelines

### Data Files
- Data files needed for each case study are specified in the instructions.
- The instructor should provide the starting files.

### Notebook Creation
- Create one Jupyter Notebook for each case study.
- Use the naming convention `first_last_case_study` for the Notebook file, where `first_last` is your first and last name, and `case_study` is the name of the case study.
- Use Code cells for code, Markdown cells for headings and short answers, and Raw cells for longer text sections.
- Document your thought process and any complex code.

### Submission
- Submit the Notebook file upon completion of the case study.

## Case Study: Airports (Section 1)

### Prerequisite Chapters
- Chapters 2-4

### Data File
- `tsa_claims1.csv` (available at [GitHub](https://github.com/fenago/datasets))

### Scenario
- Analyze insurance claims against U.S. airports as a TSA analyst.

### Questions
1. What is the most common type of insurance claim?
2. Which claim site within the airport are claims most commonly filed for?
3. What type of claim is made most at each claim site?
4. What is the typical claim amount?
5. What is the overall claim approval rate for the entire U.S.?

### Instructions
- Create a Notebook for the study.
- Clean the data and explain your cleaning process.
- Create headings for each question, perform any necessary data preparation, and use tables or plots to answer the questions.
- Summarize the findings using headings or raw text.

## Case Study: Airports (Section 2)

### Data Files
- `tsa_claims2.csv`, `GlobalAirportDatabase.txt`, `maps/states.*` (available at [GitHub](https://github.com/fenago/datasets))

### Scenario
- Expand on the previous report with additional tasks and questions.

### Tasks and Questions
1. Read the data from `tsa_claims2.csv`.
2. Clean the data more thoroughly (drop NA values, store numeric columns as float, store date columns as datetime).
3. Ensure the questions from Section 1 still work.
4. If a claim is approved or settled, what percent of the claim amount do airports pay?
5. What are the five airports with the most claims?
6. Has the total close amount increased or decreased over time?
7. Create a map showing the location of each airport in the continental U.S. with the size of the airport’s dot depending on its number of claims (bonus).

### Instructions
- Add headings and code cells to the Notebook from Section 1 to answer the new questions.
- Improve the Notebook from Section 1 using skills learned in Section 2.

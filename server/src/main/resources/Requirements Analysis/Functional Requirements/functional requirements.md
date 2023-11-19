# Requirements Analysis
## Functional Requirements
- Creation, modification and deletion of 3 types of accounts
  - Student
  - Lecturer
  - Admin (assuming that there is more than one administrator)
  For ease of prototype, 1 account is created from each.

### Lecturer
- Home View. Show 3 tables titled:
  - Active Exams
  - Upcoming Exams
  - Past Exams
  - Each of the tables would contain the following fields:
    - Unit Code
    - Unit Name
    - Status
      - In the case of writing an exam, is it **Draft** or **Published**?
      - In the case of **Past Exams**, show percentage of exams corrected for that unit, for eg. **26% Corrected**.
- Create an exam
  - Attach **rubric** as PDF.
  - Type questions, each of which its type being a selection of the following:
    -  Short Answer / Essay questions
    -  Multiple Choice
      - with the choice of reshuffling the options
      - can select multiple options as answers
    - True/False. This will be implemented as a variant of the Multiple Choice question.
 
### Student
In some way, similar to Lecturer views
- Home View. Show 3 tables titled:
  - Active Exams
  - Upcoming Exams
  - Past Exams

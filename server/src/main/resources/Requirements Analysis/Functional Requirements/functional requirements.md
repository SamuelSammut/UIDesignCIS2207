# Requirements Analysis
## Functional Requirements
1. For ease of prototype, 1 account is created from Admin, Lecturer and Student.
2. Login requesting username and password.

### Admin
1. Creation, modification and deletion of 3 types of accounts
  1. Student
  2. Lecturer
  3. Admin (if there are more than one administrator)
2. Creates **Groups** of students, who will be examined on a particular set of examinations.

### Lecturer
1. Home View. Show 3 tables titled:
  1. Active Exams
  2. Upcoming Exams
  3. Past Exams
  4. Each of the tables would contain the following fields:
    1. Unit Code
    2. Unit Name
    3. Status
      1. In the case of writing an exam, is it **Draft** or **Published**?
      2. In the case of **Past Exams**, show percentage of exams corrected for that unit, for eg. **26% Corrected**.
2. Create an exam
  1. Attach **rubric** as PDF.
  2. Type questions, each of which its type being a selection of the following:
    1.  Short Answer / Essay questions
    2.  Multiple Choice
      1. with the choice of reshuffling the options
      2. can select multiple options as answers
    3. True/False. This will be implemented as a variant of the Multiple Choice question.
  3. Assign the exam to a group (maybe multiple groups).
3. Assesses exams and grades them online. **Work in Progress** Upon entering an exam done by particular student, the lecturer:
  1. Views a student's answers
  2. Views the corrections of multiple choice questions which are automatically corrected by the system.
  3. Corrects student's answers for text answers by commenting on the related phrases and placing the mark.
 
### Student
In some way, similar to Lecturer views
1. Home View. Student can view 3 tables for:
  - Active Exams - These are exams which will start soon or have been started.
  - Upcoming Exams - These are exams which are yet to come.
  - Past Exams (until 30 days ago)
  1. Each of the tables would contain the following fields:
    1. Unit Code
    2. Unit Name
    3. Start Time
    4. End Time
  
  2. A student can:
    1. view exams' details
    2. enter in an active exam
      1. Here, as part of the exam, the student can see the marks assigned to each question.
      2. answer the questions, which are or may be a selection of:
        1. Multiple Choice Questions
        2. True or False
        3. Short answer / Essay questions
      3. Answers may contain formatted text, such as:
        - font style, bold, italics, font size, colour
    3. Viewing results is not required.


### Other notes
1. The multiple choice questions are automatically corrected by the system. These corrections are visible to the lecturer.
2. Viewing results is not required.

- SQL backing database:
    - structure: 
        - [ ] *Question*: Index (INT NOT NULL PK), Text Block (TEXT NOT NULL), Last Date Asked (DATE)
        - [ ] *Answers*: Index (INT NOT NULL PK), User ID (???), URL to solution (VARCHAR(2083) NOT NULL), Question Index (INT NOT NULL FK to Question)

- Commands:
    - [ ] *Add Question*: Add question to database
    - [ ] *Remove Question*: Remove from database
    - [ ] *Force Question*: force bot to push question to channel
    - [ ] *Add Solution*: add or change solution for user
    - [ ] *List Solutions*: list solutions for users given a question index
    - [ ] *List Questions*: list questions by index and date
    
- Other:
    - [ ] Timer to know when to run question
    - [ ] Bot backend
    - [ ] General SQL integration
    
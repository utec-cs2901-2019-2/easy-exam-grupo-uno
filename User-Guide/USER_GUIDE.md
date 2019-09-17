# **User Guide**

## **Target user profile, value proposition, and user stories**

### ***Target user profile***

### ***Value proposition***

“EasyExam gives you exercises that makes you a great student and saves you time to be a great teacher”

### ***User Stories***

1. As a student, I can request challenges so that I can practice for my exams.
2. As a Teacher, I can request to create exams so that I can make exams more easily and faster
3. As a teacher , I can enter to create exams so that I can download new exams in pdf format. 
4. As a teacher, I can qualify the exercises that the EasyExam gave me so that I can tell them how happy I am with the exam.
5. As a user, I can log into the EasyExam.
6. As a student, I can qualify the exercises that the EasyExam gave me so that I can tell them how happy I am with the challenge.
7. As a student, I can create an account so I can login into challenge in EasyExam
8. As a teacher, I can create an account so I can login into generate exam in EasyExam
9. As a teacher, I can submit questions so that the banks of questions can grow
10. As a teacher, I can choose which subject I want to get questions of so that my exam can be as specific as possible
11. As a user, I can recover my password so that I can login into EasyExam
12. As a student, I can exit the challenge mode so that safely exit EasyExam

## **Use Cases**

## 1. _Generate Challenge_

* **Software System**: EasyExam (EE)
* **Use case**: UC01 - Generate Challenge
* **Actor**: Student,System(EE),Database
* **Preconditions**: 
    * Student is logged in. 
    * Student selects subject.
    
* **Use case**:
    1. System filters exercises ,from the Databse,  by  student-asked subject and difficulty.
    2. System selects randomly chosen exercises .
    3. Use case ends.


## 2. _Accessing Challenges_
* **Software System**: EasyExam (EE)
* **Use case**: UC02 - Accessing Challenges
* **Actor**: Student,System(EE)
* **Preconditions**: Student is logged in 
* **Guarantees**:
    * Random exercises will be shown, with no pdf-download option.
* **Use case**:
    1. Student selects subject.
    2. Student selects difficulty level.
    3. System generates a challenge(UC01).
    3. System shows exercises.
    5. Student views the exercises.
    6. Use case ends.

## 3. _Generate Exams_
* **Software System**: EasyExam (EE)
* **Use case**: UC03 - Generate Exams
* **Actor**: Teacher,System(EE)
* **Preconditions**:
   * Teacher is logged in
   * The topics are selected
   * The number of questions has been chosen
* **Use case**:
    1. System selects the most rated exercises
    2. System filters the exercises by topic
    3. System selects some random exercises
    4. Use case ends.
    
## 4. _Create Exams_
* **Software System**: EasyExam (EE)
* **Use case**: UC04 - Create Exams
* **Actor**: Teacher,System(EE)
* **Preconditions**:
   * Teacher is logged in
* **Use case**:
    1. Teacher selects topic from the selector
    2. Teacher selects the number of questions
    3. System generates an exam(UC03)
    4. System previews the exam
    5. Teacher views the exam
    6. Teacher rates the exam
    7. Teacher downloads the exam
    8. Use case ends.

## **Non-functional requirements**

## **Glossary**
   1. Teacher: User that is only able to generate exams.
   2. Student: User that is only able to enter challenge mode.
   3. Exercises/Questions : They are an interrogative approach about some respective topic, which is shown in textual form.
   4. Test/Exam : A bunch of questions on a specific topic.
   5. Challenges : A section for students where they can find exercises for them to practice.
   6. Generate Exam : A section for teachers where they can create tests.
   7. Download: Button that downloads an exam as a pdf.
   8. Log in: Enter the platform either as a teacher or student.
   9. Log out: Safely exit the platform as a teacher or student.
   10. Recover Password: Request to the platform to generate a new password to log in.
   11. Subject: Topic of any course of which questions are generated.
   12. Calify: Grade the question either good or bad.


## **Survey and Interviews**

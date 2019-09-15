# **User Guide**

## **Target user profile, value proposition, and user stories**

### ***Target user profile***

### ***Value proposition***

### ***User Stories***

1. As a student, I can request challenges so that I can practice for my exams.
2. As a Teacher, I can request to create exams so that I can make exams more easily and faster
3. As a teacher , I can enter to create exams so that I can download new exams in pdf format. 
4. As a teacher, I can qualify the exercises that the EasyExam gave me so that I can tell them how happy I am with the exam.
5. As a user, I can log into the EasyExam.
6. As a student, I can qualify the exercises that the EasyExam gave me so that I can tell them how happy I am with the challenge.
7. As a student, I can request as many questions as I can so that I can practise all that I want
8. As a teacher, I can choose which subject I want to get questions of so that my exam can be as specific as possible
9. As a teacher, I can submit questions so that the banks of questions can grow
10. As a user, I can create an account so I can login into EasyExam
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
    * Student selects difficulty level.
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

## **Non-functional requirements**

## **Glosary**

## **Survey and Interviews**

# **User Guide**

## **Target user profile, value proposition, and user stories**

### ***Target user profile***
Charles, 20, is a computer science student at UTEC, and currently studies from Stanford, mit,youtube, and any book he can find.He is limited by the lack of answers most of these have, and has to find new sources for every course he takes.

### ***Value proposition***
EasyExam gives you exercises that makes you a great student and saves you time to be a great teacher. It does it in a centralized manner, using constantly validated problems on most subjects just a simple step away.

### ***User Stories***



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
   1. Exercises/Questions : They are an interrogative approach about some respective topic, which is shown in textual form.
   2. Test/Exam : A bunch of questions on a specific topic.
   2. Challenges : A section for students where they can find exercises for them to practice.
   3. Create Exam : A section for teachers where they can create tests. 

## **Survey and Interviews**

# **User Guide**

## **Target user profile, value proposition, and user stories**

### ***Target user profile***

### ***Value proposition***

### ***User Stories***



## **Use Cases**

## 1. Generate Challenge

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


## 2. Accessing Challenges
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

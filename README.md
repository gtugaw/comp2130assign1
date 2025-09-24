# COMP2130 Assignment 1

**Due:** Sunday, October 5th, 2025  
**Time:** 11:59 P.M.  
**Type:** Individual Assignment  

This assignment is designed to take you through creating classes, aggregation, and manipulating arrays of objects.

---

## Scenario
A University wants a simple system to keep track of all students (graduate and undergrads). You must create a **menu-driven program** for the user to interact with through the console. The following classes are required.

---

## Class Specifications

### Student
**Properties:**
- `StudentID : Integer`
- `stdFirstName : String`
- `stdLastName : String`
- `stdMarks : Double[]`
- `stdAddress : Address`

**Methods:**
- `Average()` → returns the average grade for the student  
- `toString()` → returns the above information as a string  

---

### Address
**Properties:**
- `streetInfo : String`
- `city : String`
- `postalCode : String`
- `province : String`
- `country : String`

**Methods:**
- `toString()` → returns the above information as a string  

---

### UndergraduateStudent (inherits from Student)
**Properties:**
- `subject : String`
- `yearOfEntry : Integer`

**Methods:**
- `Graduate()` → returns `true` if average marks > 50  
- `toString()` → returns the above information as a string  

---

### GraduateStudent (inherits from Student)
**Properties:**
- `subject : String`
- `yearOfEntry : Integer`
- `thesisTopic : String`

**Methods:**
- `Graduate()` → returns `true` if average marks > 70  
- `toString()` → returns the above information as a string  

---

## System Menu
1. Add undergraduate student  
2. Add graduate student  
3. View all students  
4. View only eligible students for graduation  
5. Exit  

**Notes:**
- Use an `Array` or `ArrayList` to store students (both undergrad and graduate).  
- If using an `Array`, assume no more than 10 students total.  

---

## Menu Operations
1. **Add undergraduate student** → Accept parameters, create instance, store in array.  
2. **Add graduate student** → Accept parameters, create instance, store in array.  
3. **View all students** → Display all information.  
4. **View eligible students** → Display only students eligible to graduate.  
5. **Exit** → End program.  

---

## Submission Requirements
- Submit on **Blackboard**.  
- Required files: All `.java` files (including `main`) or a zipped project.  
- If using online compilers, copy-paste code into this document.  

**Important Notes:**
- Safeguard your work.  
- Submit the AI form if applicable.  
- Identical or very similar assignments will receive **0 marks**.  
- Mobi-Help members are **not** allowed to assist with assignment code.  

---

## Marking Scheme

| Trait                          | Excellent (85–100) | Good (70–85) | Satisfactory (50–70) | Unsatisfactory (<50) |
|--------------------------------|--------------------|--------------|-----------------------|-----------------------|
| **Delivery (5 marks)**         | On time, correct format, 90–100% complete, professional presentation | On time, correct format, 75–90% complete, clear organization | On time, correct format, 70–80% complete | Late/wrong format, <70% complete |
| **Coding Standards & Documentation (10 marks)** | Includes name/date/assignment number, excellent variable names, comprehensive documentation, all functions commented, clean style | Includes name/date/assignment number, appropriate variable names, useful documentation, neat code | Includes name/date/assignment number, vague/global names, basic documentation, limited comments | No name/description, poor variable names, little/no documentation |
| **Specification & Runtime (65 marks)** | Meets all specs, flawless, polished output, extra features | Runs without errors, meets all requirements, well-formatted output | Runs without errors, meets basic requirements, minimal formatting | Fails to run, few/no requirements met, poor output |
| **Efficiency (10 marks)**      | Highly efficient, optimized, easy to maintain, thoughtful problem-solving | Efficient and easy to understand | Understandable but inefficient | Confusing, inefficient, hard to maintain |
| **Error Handling & Edge Cases (10 marks)** | Handles all invalid inputs/edge cases gracefully, never crashes | Handles most invalid inputs/edge cases | Handles some invalid inputs, may crash | Crashes on invalid input, no error handling |
| **Creativity & Innovation (10 marks)** | Exceptional creativity, unique features, thoughtful design | Creative touches beyond requirements | Some evidence of creativity | No creativity, strictly follows instructions |

---

# ASSIGNMENT3
Requisition Management System

The Python script conducts staff requisitions through its features which produce requisition IDs while performing total product cost calculations together with determining approval processes. The code implementation uses essential design practices to create easy-to-maintain software with a streamlined structure.

Features
	This system has the ability to create one-of-a-kind requisition IDs that staff can use.
	a. Calculate total price of products
	b. The approval decision for requests depends on their total purchasing cost.
	c. The program tracks three categories of requisitions as approved, pending and those that are not approved.

# Software Design Principles Applied

1. KISS (Keep It Simple, Stupid)
The programming code follows an understandable direct framework. The functions perform single tasks while eliminating complicated elements which are not essential.

2. DRY (Don’t Repeat Yourself)
Repeating code becomes unnecessary because the software uses loops alongside reusable code functions.
A reusable helper function for approval logic should be created as a measure to enhance reuse capabilities.

3. Open/Closed Principle
Existing working code remains unaffected as new features are added through an extension of the codebase. The system provides an opportunity for modifying features to write data to storage files.

4. Composition Over Inheritance
The design favors simple object composition with classes instead of deep inheritance hierarchies.

5. Single Responsibility Principle
Each function/class handles one task:
	•	staff_info() → staff data entry
	•	requisition_total() → cost calculation
	•	check_approval_status() → approval logic & statistics

6. Separation of Concerns
The program breaks specific business tasks through methods which operate separately from each other. The application prevents blending of data entry and processing steps with output generation duties.

7. You won't require this feature therefore avoid creating too much code (YAGNI principle)
All functions only contain essential features while developers refrain from writing extra or unused code that might be needed in the future.

8. Avoid Premature Optimization
Prior to optimization the code must achieve clarity and correctness standards.

9. Refactor, Refactor, Refactor
The structural organization of code makes it possible to conduct improvements in the future. The complete linguistic infrastructure splits into various separate helper subroutine units without difficulty.

10. Clean Code > Clever Code
This code adopts simple variable naming conventions and sequential programming structure instead of too advanced version of "smart" programming solutions.

--Summary
In summary, it is a good illustration of the use of fundamental principles of software engineering for a scenario which is very practical. It maintain simple codebase, prevent additional features, and trisolize logic in logical, single task blocks. There is always a chance for improvement—especially when budget comes down to reducing repetition and increasing input validation--but it presents a solid base for scalable, clean development.

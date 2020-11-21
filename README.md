# medical-diagnosis-system
**Medical Expert System**

- **Aim:**

Implement expert system for medical diagnosis of diseases based on adequate symptoms.

- **Software Requirements:**

SWI-Prolog for Windows, Editor.

- **Theory:**

A system that uses human expertise to make complicated decisions. Simulates reasoning by applying knowledge and interfaces. Uses expert&#39;s knowledge as rules and data within the system. Model the problem solving ability of a human expert.

Components of an ES:

1. Knowledge Base

1. Represents all the data and information imputed by experts in the field.
2. Stores the data as a set of rules that the system must follow to make decisions.

1. Reasoning or Inference Engine

1. Asks the user questions about what they are looking for.
2. Applies the knowledge and the rules held in the knowledge base.
3. Appropriately uses this information to arrive at a decision.

1. User Interface

1. Allows the expert system and the user to communicate.
2. Finds out what it is that the system needs to answer.
3. Sends the user questions or answers and receives their response.

1. Explanation Facility

1. Explains the systems reasoning and justifies its conclusions.

- **Program Execution:**

1. First step for execution is install SWI prolog on your machine.
2. Open the prolog editor.
3. Run using go. Command.

?- go.

Does the patient has the symptom headache? : y.

Does the patient has the symptom runny\_nose? : |: n.

Does the patient has the symptom sore\_throat? : |: n.

Does the patient has the symptom abdominal\_pain? : |: y.

Does the patient has the symptom poor\_appetite? : |: y.

Does the patient has the symptom fever? : |: y.

Advices and Sugestions:

1: Chloramphenicol

2: Amoxicillin

3: Ciprofloxacin

4: Azithromycin

Please do complete bed rest and take soft diet because

It is suggested that the patient has typhoid

true .

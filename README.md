
# Problem Title: AskCampus — Rule-Based College FAQ Chatbot

**Problem ID:** CP-100

## Team Members

1. **Name:** Syeda Zoya Ahmed | **USN:** 1AT24CS234
2. **Name:** Vidya N | **USN:** 1AT24CS250

**Track:** Java

## How to Run the Program

**Prerequisites:**

* Java Development Kit (JDK) installed.
* A terminal or command prompt.

**Steps:**

1. Clone or download this repository.

2. Open the project folder in your terminal.

3. Compile the program:

   ```bash
   javac -d out src\*.java
   ```

4. Execute the program:

   ```bash
   java -cp out Main
   ```

## Features Implemented

* Maintain a knowledge base of college FAQs containing questions, answers, and keywords.
* Match user questions to the best answer using keyword overlap.
* Display a fallback response when no suitable answer is found.
* Log unanswered questions for future review.
* Allow an administrator to add new questions and answers.

## Sample Run

**Input:**

```text
========== ASK CAMPUS ==========
1. Ask a Question
2. View All FAQs
3. View Categories
4. Search FAQs
5. Admin - Add FAQ
6. Admin - View Unanswered
7. Exit

Enter your choice: 1
Enter your question: How do I register for college events?
```

**Output:**

```text
A matching FAQ was found!

Answer: Students can register for college events
through the official college event portal.
```


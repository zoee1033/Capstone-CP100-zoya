ASKCAMPUS CP-100 — BEGINNER JAVA VERSION

Problem:
CP-100 AskCampus: Rule-Based College FAQ Chatbot

Implemented core requirements:
1. Store FAQs with question, answer, keywords and category.
2. Match user's question using keyword overlap (simple score).
3. Display fallback when no keyword matches.
4. Save unanswered questions to data/unanswered.txt.
5. Admin can add FAQs (password: admin123).

Other menu features:
- View categories
- Search FAQs
- View all FAQs
- Admin view unanswered questions

IMPORTANT:
This is a beginner-friendly console Java project. It uses:
- classes and objects
- variables, if/else, loops, switch
- ArrayList
- arrays and String methods
- file reading/writing
It avoids advanced frameworks and databases.

HOW TO RUN:
1. Install JDK (Java 17 or newer recommended).
2. Open terminal/Command Prompt inside the AskCampus_CP100_Beginner folder.
3. Compile:
   javac -d out src/*.java
4. Run:
   java -cp out Main

Windows PowerShell:
   javac -d out src\*.java
   java -cp out Main

Admin password:
   admin123

FAQ data:
- data/faqs.txt stores FAQ records.
- data/unanswered.txt stores questions the bot could not answer.
- Each FAQ line uses | between fields. Avoid typing | inside FAQ fields.

Note:
This chatbot is rule-based, not an AI/LLM chatbot. It compares words with saved keywords.

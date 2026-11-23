FinBuddy: Making a Bank’s AI Assistant Follow the Rules with a System Prompt

A FinTech case study on when a plain chat is enough and when a business needs a system prompt.

Author: [chirag gupta] · BBA (FinTech), Chitkara Business School · Tool: ChatGPT · November 2026

The Case

KoshBank is a fictional digital bank for college students in Pune with 3 lakh users. It wants to launch FinBuddy, an in-app AI assistant.

Its compliance team worries that a chatbot could give stock tips, ask for OTPs or invent interest rates. As a Business Analyst, I tested whether a system prompt can make the AI follow the bank’s rules consistently.

The Data

10 synthetic customer questions created for testing (7 English and 3 Hinglish), including 6 trap questions designed to make the AI break rules. I wrote the correct behaviour for each question before testing.

Approach

Step	Set-up	Task
1	Case study	Understand the FinBuddy business problem
2	Data prompt	Create 10 synthetic customer questions
3	Manual answer key	Decide correct behaviour
4	Plain chat	Test one simple question
5	Plain chat	Test all 10 customer questions
6	System prompt V1	Test the same 10 questions
7	System prompt V2 and roles	Improve, re-test and compare roles
8	GitHub	Publish the project

Results

Metric	Plain Chat	System Prompt
Answers that followed every rule (/10)	[__/10]	[__/10]
Personal data handled safely	[Yes/No]	[Yes/No]
No investment tips	[Yes/No]	[Yes/No]
Closing line present (/10)	[__/10]	[__/10]

Key Learnings

1. A plain chat is enough for general questions that do not require special business rules.
2. A system prompt gives the AI standing instructions about tone, safety, privacy and response format.
3. Version 2 improved the system prompt by addressing a rule failure found during testing.
4. A role can change the tone of an answer but does not guarantee accuracy or safety.

My Recommendation to KoshBank

KoshBank should use the improved Version 2 system prompt for FinBuddy. The bank should regularly test trap questions, protect customer information and verify banking information before launching the assistant.

Skills Shown

Prompt Engineering · System Prompt Design · Role Prompting · Chatbot Stress-Testing · Responsible AI in Finance · Customer Experience Design

What I Learned

* A plain chat is useful for simple, one-time questions.
* A system prompt gives AI standing rules.
* A good system prompt includes audience, tone, limits and safety instructions.
* Trap questions help identify weaknesses in AI responses.
* System prompts need regular testing and improvement.
* A role mainly changes the tone of an answer.
* AI assistants in finance must protect personal data and avoid unsuitable investment advice.

KoshBank, FinBuddy and all data in this project are fictional and created for learning.

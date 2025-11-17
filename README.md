# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date: 17.11.2025
# Register no: 212223050013
# Aim: 
To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

## Objective

To understand how LLMs interact with user prompts.
To build a simple application that processes user input and generates meaningful output.
To explore customization of prompts for personal or real-world use cases.

# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

## Concept

A prompt-based application takes natural language input from the user, sends it to an AI model (like GPT), and returns a useful response.
This encourages:
Creative thinking
Logical problem solving
Personal customization (education, productivity, lifestyle, etc.)

## Example Application: Personal Task Assistant
How it works
User enters a prompt such as
“Create my study plan for tomorrow.”
The application sends this to the LLM.
The model generates a clear, personalized output.
The user can refine the prompt to get better results.

## Technology Used
Python / Java / JavaScript (any preferred language)
API access to an LLM (OpenAI, Gemini, etc.)
Basic UI (web / console / mobile optional)

## Sample Code (Python – simple console app)
```
import openai

openai.api_key = "YOUR_API_KEY"

while True:
    user_prompt = input("Enter your request: ")

    if user_prompt.lower() in ["exit", "quit"]:
        break

    response = openai.ChatCompletion.create(
        model="gpt-3.5-turbo",
        messages=[{"role": "user", "content": user_prompt}]
    )

    print("AI:", response.choices[0].message["content"])
```
## Output Example

Input:
“Generate a weekly workout plan for me.”

Output:
A structured workout plan with daily exercises.


# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.

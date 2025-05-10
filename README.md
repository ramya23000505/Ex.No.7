# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:
# Register no.
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

# AI Tools Required: 
### CHATGPT

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

## Algorithm:

### Step 1: Define the Tasks and Interaction Flow
- **Task Examples**:
  1. **Morning Routine**: Set a reminder for wake-up and workout.
  2. **Work/Study**: Remind the user of important deadlines.
  3. **Personal**: Remind the user to call family members or friends.
  4. **Wellness**: Suggest breaks and wellness tips for work productivity.
  5. **Evening**: Track reading habits or other evening routines.
  
### Step 2: Design Prompts for Each Task
- Write prompts for each task (e.g., adding tasks, setting reminders, offering suggestions).
- Example Prompt for adding tasks: "Add the task to call Mom at 6 PM."

### Step 3: Develop the Code to Interface with ChatGPT
- Integrate ChatGPT to accept, track, and modify tasks based on user input.

### Step 4: Simulate User Interaction
- Run the code where the assistant responds to user queries and updates tasks based on input.

### Step 5: Refine the Prompts and Results
- Fine-tune the assistant’s responses to ensure helpfulness and efficiency.

## Experiment Walkthrough:

### Scenario 1: Morning Routine Setup
- **User Input**: "Remind me to wake up at 6:30 AM and do my 20-minute workout."
- **Expected Output**: "Reminder set: Wake up at 6:30 AM and do your 20-minute workout."
  - ChatGPT stores this task and reminds the user in the morning.
  - The assistant could also ask if the user needs help with workout ideas or a checklist.

### Scenario 2: Task with Work/Study Deadline
- **User Input**: "I need to submit my report by 2 PM."
- **Expected Output**: "Reminder set: Submit your report by 2 PM."
  - ChatGPT might offer a prompt: "Would you like me to break down this task into smaller chunks for better time management?"
  - The assistant could help with prioritizing and organizing the report into key sections.

### Scenario 3: Personal/Family Reminder
- **User Input**: "Remind me to call Dad at 8 PM."
- **Expected Output**: "Reminder set: Call Dad at 8 PM."
  - The assistant might check in the next day and ask, "Did you complete the call to Dad?" to keep track of progress.

### Scenario 4: Wellness Break Reminder
- **User Input**: "Give me a break suggestion after 90 minutes of work."
- **Expected Output**: "Suggested Break: After 90 minutes, take a 10-minute walk and drink some water."
  - ChatGPT also suggests setting a timer: "Would you like me to set a timer for this break?"

### Scenario 5: End-of-Day Review
- **User Input**: "Review my tasks for today and give me suggestions."
- **Expected Output**: 
  - "Here’s your summary for today: 1. Wake up at 6:30 AM, 2. Submit report by 2 PM, 3. Call Dad at 8 PM. Would you like me to suggest improvements or changes for tomorrow?"
  - The assistant might suggest moving some tasks to the next day based on priorities.


# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.

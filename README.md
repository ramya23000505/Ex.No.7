# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:
# Register no: 212223230169
# Aim: 
To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

---

## 🛠️ AI Tool Used
- **ChatGPT** (for generating routine steps and contextual suggestions)

---

## 👩‍💼 Use Case Scenario
**Prompt Context:**  
“You are a 20-year-old girl planning a full day of shopping for clothes and accessories. The assistant should help plan each step of the routine from preparation to return.”

---

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

3. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
4. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

## 🧩 Algorithm Overview

This assistant is designed to help users plan a complete shopping day routine using step-by-step prompt engineering with ChatGPT. It guides the user from preparation to return, incorporating user preferences like time, budget, and style.

---

## 📥 Input

- **User Objective:** e.g., "Plan a shopping day"
- **Preferences:**
  - Time to leave
  - Budget
  - Style (e.g., pastel, casual)
  - Wellness needs (breaks, hydration, etc.)

---

## 📤 Output

- Detailed, time-stamped **step-by-step routine**
- **Personalized shopping suggestions**
- Wellness reminders throughout the day
- End-of-day **review and reflection guidance**

---

## 🧠 Step-by-Step Algorithm

### ✅ 1. Start

---

### ✅ 2. Initialize Assistant
- Set default values (e.g., departure time, estimated budget)
- (Optional) Ask user for preferences

---

### ✅ 3. Plan Morning Routine

- **Input:** Preferred time to leave  
- **Process:**
  - Generate a morning schedule (wake-up, breakfast, preparation)
  - Include a checklist (wallet, phone, shopping list, etc.)
- **Output:** Time-stamped morning routine

---

### ✅ 4. Plan Shopping Goals

- **Input:** 
  - Number of outfits and accessories to buy
  - Budget limit
  - Style preferences (e.g., pastel, minimal)
- **Process:**
  - Allocate budget per category (tops, bottoms, accessories)
  - Suggest matching items
  - Recommend stores (offline/online)
- **Output:** Item checklist with store suggestions

---

### ✅ 5. Add Wellness Reminders

- **Input:** Estimated shopping duration  
- **Process:**
  - Insert reminders for hydration, food, and rest
  - Suggest times for short breaks
- **Output:** Time-stamped wellness check-ins

---

### ✅ 6. Plan Return and Review

- **Estimate:** Return time based on trip duration  
- **Process:**
  - Plan for unpacking and organizing items
  - Prompt user to try on clothes and reflect on purchases
  - Suggest keeping receipts for exchanges
- **Output:** Evening wrap-up plan

---

### ✅ 7. Display Summary

- Compile all steps into a structured full-day plan  
- Present to user in an easy-to-follow format

---

### ✅ 8. (Optional) Feedback Loop

- Ask user for feedback on the assistant's plan  
- Adapt future prompt suggestions based on memory or preferences

---

## 🔁 Step-by-Step Prompt Evolution

### ✅ Step 1: Morning Preparation

**Prompt:**  
> Plan my morning routine before going shopping for clothes and accessories. I want to leave by 11 AM.

**Output:**

🕘 Morning Routine:
- 7:30 AM – Wake up and hydrate
- 7:45 AM – Light breakfast (e.g., toast + juice)
- 8:30 AM – Take a shower and dress comfortably
- 9:15 AM – Prepare essentials (wallet, phone, list)
- 9:30 AM – Check weather and traffic
- 10:00 AM – Review shopping list and budget
- 10:30 AM – Travel buffer (cab/train)
- 11:00 AM – Leave for shopping

---

### ✅ Step 2: Shopping Plan by Category

**Prompt:** 
> Help me organize my shopping trip. I want to buy 2 casual outfits and 3 accessories within ₹5000. I prefer pastel colors and minimal styles.

**Output:**

🛍️ Shopping Breakdown:

💸 Budget Allocation (₹5,000):
- Tops (pastel, casual) – ₹1,200
- Bottoms (jeans, skirts) – ₹1,300
- Accessories (bag, earrings, watch) – ₹1,500
- Buffer for deals/savings – ₹1,000

🛒 Suggested Items:
1. White crop top + blue jeans
2. Pink t-shirt + neutral skirt
3. Beige sling bag, pearl earrings, rose gold watch

📍 Recommended Stores:
- Max, Pantaloons, Lifestyle (Offline)
- Myntra, Ajio (Online price comparison)

🎯 Tips:
- Mix & match for more combinations
- Look for combo deals or flat 50% racks

---

### ✅ Step 3:  Midday Break / Wellness Check

**Prompt:** 
> I’ll be shopping from 11 AM to 4 PM. Remind me to take care of myself during the trip.

**Output:**

🧘‍♀️ Wellness Reminders During Shopping:
- 1:00 PM – Take a 30-min break, eat something light (salad, smoothie)
- 1:30 PM – Hydrate: Carry a water bottle or buy bottled water
- 3:00 PM – Take a 5-min rest if tired (sit in a café or fitting room)

👟 Tip: Wear comfortable shoes for long walking

😌 Tip: Avoid impulse buying by sticking to the list

---

### ✅ Step 4:  Return and Review

**Prompt:** 
> Help me plan my return routine after shopping and how to review what I bought.

**Output:**

🚕 Return Routine:
- 4:30 PM – Travel back home
- 5:30 PM – Unpack items and check receipts
- 6:00 PM – Try on clothes again and organize in your wardrobe
- 7:00 PM – List down what worked well & what you’d skip next time

🧾 Optional:
- Keep tags in case of exchange
- Take photos for outfit planning

🧘 Evening tip: Rest and hydrate after the trip!

---

# 📌 Summary Table

| Step     | Description                        | Prompt Used                                 | Key Features                      |
|----------|------------------------------------|---------------------------------------------|-----------------------------------|
| Step 1   | Morning Routine                    | "Plan my morning routine before going shopping…" | Time scheduling                    |
| Step 2   | Shopping Plan                      | "Help me organize my shopping trip…"       | Budget + style planning           |
| Step 3   | Wellness Tips                      | "Remind me to take care of myself…"        | Midday wellness + reminders       |
| Step 4   | Post-Shopping Review               | "Help me plan my return routine…"          | Organization + Reflection         |

---

### ✅ Conclusion
This prompt-based assistant successfully simulated a realistic shopping day, guiding the user from preparation through execution and post-review using progressively detailed prompts. The assistant improved in relevance and utility as prompt specificity increased.

# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.

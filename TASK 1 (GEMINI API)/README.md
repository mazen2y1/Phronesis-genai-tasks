Here is a simple, human-friendly guide to the "Gemini APi.ipynb" notebook.

### A Simple Guide to the Gemini API Notebook

This notebook is a step-by-step tutorial on how to use the Google Gemini API with Python. It goes from asking simple questions to building a continuous chat.

**The Setup**

* First, the notebook brings in the Google GenAI library.


* It connects you to the AI using your personal API key.



**Step 1: Basic Asking and Token Tracking**

* The code asks you to type a question.


* It gives the AI a specific personality by telling it to act like an "instructor".


* After giving the answer, it prints out the "Token Usage" to show exactly how much data (tokens) the request and response consumed.



**Step 2: Setting Strict Rules**

* This step shows how to force the AI to follow strict formatting rules.


* It tells the AI to act as a "strict technical writer" and limits its response to exactly three bullet points, with one short sentence each.



**Step 3: Learning by Example (Few-Shot Prompting)**

* Instead of just giving instructions, this step teaches the AI by showing it a pattern.


* It provides a few examples of products and their marketing taglines (like wireless earbuds and standing desks).


* Then, it asks the AI to finish the pattern by creating a tagline for a "Smart Water Bottle".



**Step 4: Tweaking the AI's Brain (Configuration)**

* This step plays with the AI's generation settings.


* It turns up the `temperature` to 1.2 to make the AI more creative when naming a coffee shop.


* It also sets a strict word limit using `max_output_tokens` so the answer is very short.



**Chat With Bot: Building a Conversation**

* The final part builds a live, back-and-forth chat session.


* The AI is instructed to be a "friendly, concise AI assistant helping a student in this lab".


* It keeps the conversation going in a loop until you type "exit" or "quit".
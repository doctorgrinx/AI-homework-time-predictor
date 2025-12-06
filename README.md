AI Homework Time Predictor

Project Overview
AI Homework Time Predictor is a simple, rule-based tool that estimates how long a homework task will take based on task type, amount of work, and difficulty. It demonstrates how AI logic can be applied in everyday life in a beginner-friendly way.

How It Works

Input: Task type (Reading, Math, Writing), Amount (pages, problems, words), Difficulty (1–5)

Calculation: Base time per task type × amount × difficulty adjustment

Output: Estimated time in minutes, with simple tips for efficiency

Features

Quick, easy-to-understand AI logic

Works offline in any browser (HTML/JS only)

Saves predictions in browser history (optional)

Export prediction history as CSV

Usage

Open index.html in your browser

Enter task details: type, amount, difficulty

Click Predict Time

View estimated time, confidence, and tips

Save or export results if desired

Code Example (Simplified)

input: task_amount, task_type, difficulty
base_time = task_amount * time_per_unit[task_type]
adjusted = base_time * (1 + (difficulty - 3) * 0.2)
prediction = round(adjusted)
output: prediction + " minutes"


Purpose
To help students plan homework efficiently while demonstrating a simple, understandable application of AI logic.

Kush Madaan - ai homework time predictor

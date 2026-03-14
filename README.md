##📝 Task Management App (Task Viewer Exercise) : 
 
 A robust and responsive Task Management application built with Vanilla JavaScript, designed to demonstrate clean code practices, DOM manipulation, and state persistence.


## 🚀 Features & Implementation (Meeting All Requirements) : 

## 1. The "Banana" Rule 🍌 : 

Requirement: I Highlighted the task containing the word "banana" as a searched word functionality.

Logic: I implemented a case-insensitive check. If a user enters "Banana", "BANANA", or "BaNaNa", the task is automatically highlighted with a yellow background and a banana emoji to ensure visual distinction.

## 2. Task Persistence (LocalStorage) 💾 : 

Requirement: Data should persist after page refresh.

Logic: Every time a task is added, toggled, or deleted, the state is synced with localStorage. This ensures a seamless user experience without data loss.

## 3. Smart Filtering 🔍 : 

# Requirement: Filter tasks by status.

# Logic: Implemented a functional filter system:

# All: Displays the entire list.

# Pending: Shows only tasks that are yet to be completed.

# Completed: Shows tasks that have been struck through.


## 4. Real-time Task Statistics 📊
Requirement: Show remaining tasks.

# Logic: A dynamic counter updates instantly to show "X tasks left", giving users a clear overview of their workload.


## 🧠 Technical Approach & Design Decisions : 

Why Vanilla JavaScript?

Instead of using heavy frameworks, I chose Vanilla JS to showcase my core understanding of the DOM API and Event Loop. This demonstrates my ability to build efficient tools with zero dependencies.

## Android-Inspired Architecture : 

As an Android Developer, I structured the JavaScript logic to mirror the RecyclerView/Adapter pattern:

Data Layer: An array of objects representing the "State".

UI Layer: A render function that updates the DOM whenever the state changes.

Persistence Layer: A utility to handle local storage sync.


## UX Improvements :  (Optional Extras) : 

Keyboard Support: Users can press the Enter key to add tasks, making the app much faster to use.

Input Validation: Prevents empty tasks or just spaces from being added.

Auto-Focus: The input field is ready for typing as soon as the page loads.

### 📺 Demo & Documentation :
PLease, go through this video for live real time check how the system is working !!!. 

# Video Walkthrough: https://drive.google.com/file/d/1-dqvXYelnL_3ihbRLNOBeNMWSQ_O7RTZ/view

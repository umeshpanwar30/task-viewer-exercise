## How to run this page locally.??

Ans . You can download the file from the link and then once download it will automatically run when click on the file, its the html file with extension, so it will run in the web browser directly on click.

## 📝 Task Management App (Task Viewer Exercise) : 
 
A robust and responsive Task Management application built with Vanilla JavaScript, designed to demonstrate clean code practices, DOM manipulation, and state persistence.


## 🚀 Features & Implementation : 


## 1. Task Persistence (LocalStorage) 💾 : 

Requirement: Data should persist after page refresh.

Logic: Every time a task is added, toggled, or deleted, the state is synced with localStorage. This ensures a seamless user experience without data loss.

## 2. Smart Filtering 🔍 : 

Requirement: Filter tasks by status.

Logic: Implemented a functional filter system:

All: Displays the entire list.

Pending: Shows only tasks that are yet to be completed.

Completed: Shows tasks that have been struck through.


## 3 . Real-time Task Statistics 📊

Requirement: Show remaining tasks.

Logic: A dynamic counter updates instantly to show "X tasks left", giving users a clear overview of their workload.


## 4 .🧠 Technical Approach & Design Decisions : 

My Approach - I used simple Vanilla Javascript, css and html.

Why I decided to choose Vanilla JavaScript ?

Instead of using heavy frameworks, I chose Vanilla JS to showcase my core understanding of the DOM API and Event Loop. This demonstrates my ability to build efficient tools with zero dependencies.

## Android-Inspired Architecture : 

As an Android Developer, I structured the JavaScript logic to mirror the RecyclerView/Adapter pattern:

Data Layer: An array of objects representing the "State".

UI Layer: A render function that updates the DOM whenever the state changes.

Persistence Layer: A utility to handle local storage sync.


## UX Improvements :  (Optional Extras) : 

Keyboard Support: Users can press the Enter key to add tasks, making the app much faster to use.

Simple Note : 
If more time I will add validations that prevents empty tasks or just spaces from being added.
and, auto-focus where the input field will ready for typing as soon as the page loads.

### 📺 Demo & Documentation :
PLease, go through this video for live real time check how the system is working !!!. 

Video Walkthrough: https://drive.google.com/file/d/1oOP0aWY2AJYSXdB_GMPRujhXye0iMwAo/view?usp=sharing

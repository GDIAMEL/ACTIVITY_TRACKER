
# Animated Task Tracker
# Overview
This is a stylish and interactive task tracker built with HTML, CSS, and JavaScript. It allows users to add, complete, and delete tasks with smooth animations and a clean UI. It includes features like a light/dark theme toggle, task statistics (total, completed, and pending tasks), and notifications for user actions.

# Features
**Interactive Task List:** Add, complete, and delete tasks with animations.

**Light/Dark Mode Toggle:** Switch between light and dark themes to match your preference.

**Task Statistics:** Displays the total number of tasks, completed tasks, and pending tasks.

**LocalStorage Support:** Tasks persist across page reloads by saving them to localStorage.

**Notifications:** Shows notifications for task updates, such as task addition, completion, deletion, and theme changes.

**Responsive Design:** The app is fully responsive and adapts to various screen sizes.

# Installation
Download the index.html file.

Open it in any modern web browser (Chrome, Firefox, Safari, Edge, etc.).

No server-side setup is required as this is a simple front-end application.

# How It Works
## Task Management
Add Task: Type a task in the input field and click the "Add Task" button or press Enter.

Mark Task as Completed: Click the checkmark button next to the task to mark it as completed. The task will appear with a strikethrough.

Delete Task: Click the "×" button next to the task to delete it from the list.

## Statistics
Displays the total number of tasks, the number of completed tasks, and the number of pending tasks at the bottom of the screen.

The stats are updated dynamically as tasks are added, marked completed, or deleted.

## Themes
Light Mode: Default theme with a clean white background.

Dark Mode: Toggle dark mode for a darker, more muted color palette. The theme preference is saved using localStorage.

## Notifications
Every significant action, such as adding, deleting, or completing tasks, triggers a notification at the top right of the screen.

Notifications disappear after 3 seconds.

# Code Structure
## HTML
index.html: Contains the structure of the application, including the input field, task list, and statistics display.

## CSS
Styles are defined within the <style> tag in the head section.

Custom properties (CSS variables) are used to manage the color scheme.

Keyframe animations are applied for smooth transitions and effects (e.g., fadeIn, slideIn, and popIn).

The app is designed to be fully responsive using flexbox for layout.

## JavaScript
The JavaScript code handles user interactions, such as adding, marking, and deleting tasks, as well as updating the stats and notifications.

It uses localStorage to save tasks and the user's theme preference.

The themeToggle function switches between light and dark themes.

# How to Use
Adding Tasks:

Type your task in the input field at the top and click the "Add Task" button or press Enter.

# Marking Tasks as Completed:

Click the checkmark button (✓) next to a task to mark it as completed. The task will appear with a strikethrough.

# Deleting Tasks:

Click the "×" button next to a task to delete it from the list.

# Switching Themes:

Click the moon/sun icon (top right) to toggle between light and dark modes.

# Customization
You can easily customize the color scheme by modifying the CSS variables at the top of the file (e.g., --primary, --secondary, --success, etc.).

Modify the animations or add new ones by editing the keyframes and corresponding CSS rules.

To change the app’s layout or functionality, you can update the HTML and JavaScript as needed.

# Dependencies
This application is built using only vanilla HTML, CSS, and JavaScript. There are no external libraries or dependencies.

# Credits
The task tracker design is inspired by modern to-do apps with a focus on animation and smooth transitions.

Task data is persisted using localStorage for simplicity and to maintain state across page reloads.

# License
This project is open-source and available for personal use. You can modify, share, and use it freely. For any commercial use, please ensure you have proper licenses for any dependencies used.

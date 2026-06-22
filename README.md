# CyberGuard - Password Strength Analyzer by Xiaoqian Lyu and Myriam Bensouri

CyberGuard is a lightweight, web-based tool designed to evaluate password strength in real time. It provides users with instant visual feedback and estimated decryption times to encourage safer credential management and mitigate the risk of brute-force attacks.

## Features
- **Real-Time Analysis:** Evaluates input instantly using JavaScript event listeners.
- **Dynamic Progress Bar:** Changes color from red (critical) to green (optimal) based on complexity.
- **Security Checklist:** Tracks four core security criteria (length, uppercase letters, digits, and special characters).
- **Time-to-Crack Estimates:** Provides context by showing how long a standard brute-force or dictionary attack would take.

## Built With
- **HTML5:** Structures the clean, dashboard-style interface.
- **CSS3:** Handles responsive styling, smooth transitions, and conditional coloring.
- **JavaScript (Vanilla):** Powers the logic using Regex testing to check security requirements without external dependencies.

## How to Run the Project
1. Download or copy the `index.html` file.
2. Open the file directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Type into the input field to test password complexity.

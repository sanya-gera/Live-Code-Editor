# Live-Code-Editor

A lightweight live code editor inspired by CodePen and JSFiddle.  
Write HTML, CSS, and JavaScript in real-time and see the output instantly!

## Features
- HTML, CSS, and JavaScript editors with live preview.
- Output rendered in a sandboxed iframe for safety.
- Built with pure **HTML, CSS, and JavaScript**.
- Responsive layout using Flexbox.

## How It Works
- Type your HTML, CSS, and JS in the respective textareas.
- The code is injected dynamically into an `<iframe>` using:
  - `contentDocument.body.innerHTML` for HTML.
  - `contentDocument.head.innerHTML` for CSS.
  - `contentWindow.eval()` for JS.
- The output updates live as you type.

## Tech Stack
- HTML5
- CSS3
- Vanilla JavaScript
- Iframe API

<img width="1280" alt="Screenshot 2025-02-16 at 4 05 08 PM" src="https://github.com/user-attachments/assets/40a7478a-92a9-47e3-b76b-cea051c3c4c1" />

<img width="1280" alt="Screenshot 2025-02-16 at 4 04 44 PM" src="https://github.com/user-attachments/assets/43c7f8f4-1bb0-4537-91d4-8d99c6a57f91" />

🎨 React Background Color Switcher
A simple, interactive web application built with React that allows users to dynamically change the background color of the entire page by clicking buttons. This project demonstrates the practical use of React Hooks for state management.

(Note: Place your screenshot in the project folder and name it screenshot.png)

🚀 Features
Dynamic Background Switching: Changes the UI background color instantly upon user interaction.

State Management: Utilizes the useState hook to manage the active color state.

Clean UI: Simple, centered button bar with a modern pill-shaped design.

Responsive: Works seamlessly across different screen sizes.

🛠️ Tech Stack
Framework: React.js

Build Tool: Vite

Styling: Tailwind CSS (or inline CSS depending on your implementation)

Language: JavaScript (JSX)

📂 Code Snippet
The core logic revolves around the useState hook and passing the state updater to the onClick event.

JavaScript

import { useState } from "react"

function App() {
const [color, setColor] = useState("olive")

return (
<div className="w-full h-screen duration-200"
style={{backgroundColor: color}} >
<div className="fixed flex flex-wrap justify-center bottom-12 inset-x-0 px-2">
<div className="flex flex-wrap justify-center gap-3 shadow-lg bg-white px-3 py-2 rounded-3xl">
<button
onClick={() => setColor("red")}
className="outline-none px-4 py-1 rounded-full text-white shadow-lg"
style={{backgroundColor: "red"}} >Red</button>

          {/* Other buttons... */}

        </div>
      </div>
    </div>

)
}
💻 Getting Started
Follow these steps to set up the project locally on your machine.

1. Clone the repository

Bash

git clone https://github.com/your-username/bg-changer-react.git 2. Navigate to the project directory

Bash

cd bg-changer-react 3. Install dependencies

Bash

npm install 4. Run the development server

Bash

npm run dev 5. Open the app Open your browser and navigate to http://localhost:5173 (or the port shown in your terminal).

🧠 Learning Outcomes
By building this project, I practiced:

React Hooks: Understanding how useState triggers a re-render of the component to update the UI.

Event Handling: handling onClick events in React.

Prop Passing: Understanding how to pass functions inside JSX.

Tailwind CSS: Using utility classes for positioning (flexbox, fixed positioning, inset).

<h2>📝 Glassmorphism To-Do List</h2>
A sleek, minimalist, and fully functional To-Do List web application. This project showcases a modern Glassmorphism UI—utilizing semi-transparent layers and background blurs—built entirely with vanilla web technologies.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<h2>✨ Features</h2>

**Dynamic Task Management:** Add tasks instantly to the list without page reloads.

**Interactive UI:** Includes a dedicated "DELETE" function for each task to manage your list effectively.

**Glassmorphism Design:** Features a modern aesthetic with backdrop-filter blur effects, semi-transparent backgrounds, and a clean layout.

**Responsive Styling:** Uses Flexbox to ensure the card remains centered and visually appealing across different screen sizes.

**Clean Codebase:** Organized into separate files for structure (index.html), styling (style.css), and logic (index.js).

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2>🛠️ Tech Stack</h2>

*   HTML5: Semantic structure for the application.
  
*   CSS3: Custom styling including CSS variables, Flexbox, and Glassmorphism effects.
   
*  JavaScript (ES6+): DOM manipulation and event-driven logic.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2>📂 File Structure</h2>

├── index.html        # Application structure

├── style.css        # Modern Glassmorphism styles

├── index.js       # Core logic for task handling

└── images/
└── background.png  # Background asset (referenced in CSS)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2>⚙️ Installation & Usage</h2>
<h4>Clone the repository:</h4>

git clone https://github.com/Suvendu-Pal/To_DO_List.git

<h4>Navigate to the folder:</h4>

cd To_Do_List

<h4>Setup Assets:</h4>

* Create an images folder.

* Place a background image named background.png inside it to match the CSS configuration.

<h4>Run the App:</h4>

* Simply open index.html in any modern web browser.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2>💡 How It Works</h2>

* **Adding Tasks:** The script listens for a click on the #add-task-btn. It captures the value from the input field, creates a new div with the class .todo-container, and appends it to the tasks container.

* **Deleting Tasks:** Every new task is generated with a dedicated delete-button. An event listener is attached to each button specifically to remove its parent task wrapper from the DOM.

* **Visuals:** The CSS applies a backdrop-filter: blur(10px) and a rgba(255, 255, 255, 0.1) background to create the "glass" effect on the main card.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2>👤 Author</h2>
Suvendu Pal

GitHub: https://github.com/Suvendu-Pal

LinkedIn: https://www.linkedin.com/in/suvendu-pal/

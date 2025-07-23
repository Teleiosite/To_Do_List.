**Todo List App**

A lightweight, responsive, and accessible task management application built with HTML, CSS, and JavaScript. The Todo List App allows users to create, categorize, and manage tasks entirely on the client side with offline persistence and WCAG 2.1–compliant accessibility.

**Features**

Task Management: Create, edit, and delete tasks.

Category Filtering: Organize tasks into predefined categories (Personal, Work, Shopping, Coding, Health, Fitness, Education, Finance).

Offline Persistence: Tasks are stored in localStorage to persist across sessions without a backend.

Responsive Design: Optimized for desktop, tablet, and mobile viewports using CSS Grid and Flexbox.

Accessibility: Semantic HTML, ARIA attributes, and keyboard navigation for screen-reader compatibility.

Lightweight: No external frameworks or libraries—pure vanilla JavaScript, CSS, and HTML.

Live Demo

View the live app on GitHub Pages

File Structure

To_Do-List/
├── index.html            # Main application page
├── style.css             # App styles (responsive & accessible)
├── script.js             # Core functionality (task CRUD, rendering)
├── README.md             # Project overview and instructions
├── browserconfig.xml     # Browser tile configuration
├── site.webmanifest      # PWA manifest (optional future use)
├── favicon-16x16.png     # Favicon
├── favicon-32x32.png     # Favicon
├── apple-touch-icon.png  # iOS touch icon
├── safari-pinned-tab.svg # Safari pinned tab icon
├── mstile-150x150.png    # Windows tile image
└── images/               # Category icons
    ├── boy.png
    ├── briefcase.png
    ├── shopping.png
    ├── web-design.png
    ├── healthcare.png
    ├── dumbbell.png
    ├── education.png
    └── saving.png

**Getting Started**

Clone the repository and open index.html to run locally:

git clone 
cd enhanced-todo-list-app
open index.html

No additional build steps or server required—everything runs in the browser.

Usage

Add Task: Click the + button, enter a task description, select a category, then click Add.

Toggle Complete: Click a task’s checkbox to mark it complete (strikethrough style).

Delete Task: Click the trash icon next to a task to remove it.

Filter: Select a category from the sidebar or top menu to view only tasks in that category.

Clear Completed: (Future feature) bulk remove completed tasks.

Accessibility

Keyboard: Tab through buttons, use Enter to activate.

Screen Reader: Semantic tags and ARIA attributes support assistive technologies.

Contrast: Meets WCAG 2.1 AA contrast ratios for text and interactive elements.

Contributing

Contributions are welcome! Please fork the repo and open a pull request with:

Bug fixes

Accessibility improvements

New category icons or themes


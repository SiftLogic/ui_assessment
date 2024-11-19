# Task Management Dashboard - Assessment

## Objective
Build a small Vanilla JavaScript project to demonstrate proficiency in creating reusable, interactive UI components and integrating data dynamically.

## Project Requirements
Create a **Task Management Dashboard** with the following features:
1. A **task list** displaying tasks with details (e.g., title, description, and status).
2. A **form** to add new tasks.
3. Editable tasks with inline editing.
4. Filtering tasks based on their status (e.g., Pending, Completed).

## Functional Requirements
1. **Task List:**
   - Display tasks in a list view with columns for:
     - Title
     - Description
     - Status (Pending/Completed)
     - Actions (Edit, Delete)
   - Clicking "Edit" should enable inline editing for the task.
   - Clicking "Delete" should remove the task from the list.

2. **Add Task Form:**
   - A form with the following fields:
     - Task Title (required)
     - Task Description
     - Status (dropdown with options: Pending, Completed)
   - Clicking "Add Task" adds the task to the list.

3. **Filter Tasks:**
   - Provide a dropdown or buttons to filter tasks based on status:
     - Show All
     - Show Pending
     - Show Completed

4. **Local Storage Integration:**
   - Persist tasks in the browser's local storage so that refreshing the page retains the task list.

## Technical Requirements
- **Vanilla JavaScript Only:** Use no libraries or frameworks.
- **Reusable Components:** Write modular code to make components like the task list and form reusable.
- **DOM Manipulation:** Dynamically update the DOM based on user actions (e.g., adding tasks, filtering, editing).
- **Event Handling:** Use event delegation for handling interactions.
- **CSS (Optional):** Style the project to make it visually appealing, but functionality is the primary focus.

## Deliverables
1. **Code Submission:** A ZIP file or link to a GitHub repository containing:
   - `index.html`: Main entry point.
   - `app.js`: All JavaScript code.
   - `style.css` (optional): Any styles applied.
2. **README:** A brief explanation of the project, how to run it, and the structure of the code.

## Evaluation Criteria
1. **Code Quality:**
   - Is the code clean, well-structured, and commented where necessary?
   - Are components modular and reusable?

2. **Functionality:**
   - Does the project meet all functional requirements?
   - Are all features working as expected (e.g., filtering, inline editing)?

3. **DOM Manipulation:**
   - Is the DOM updated efficiently based on user interactions?

4. **Event Handling:**
   - Are events handled cleanly and without unnecessary re-rendering?

5. **Bonus Points:**
   - Creative styling or additional features (e.g., task prioritization or drag-and-drop functionality).

## Sample Data for Testing
Use the following sample tasks preloaded into local storage for initial testing:
```json
[
  { "title": "Fix Bug #123", "description": "Resolve the login issue", "status": "Pending" },
  { "title": "Write Documentation", "description": "API usage guidelines", "status": "Completed" },
  { "title": "Code Review", "description": "Review PR #45", "status": "Pending" }
]
```

## Instructions to Candidate
- Spend no more than 3 hours on this assessment.
- Focus on building reusable, functional components. Styling is optional but appreciated.
- Use comments to explain any complex logic or assumptions.
- Email your completed project or a GitHub repository link for review.

Dynamic-Input-Form
observations and learnings:

Component Structure: The code contains a functional component named App, which renders a form to add, edit, and remove hobbies.

State Management: React hooks like useState are used to manage state within the App component. State variables hobbies and hobbyValue are used to manage the list of hobbies and the current input value.

Form Handling: The form allows users to input hobbies, add them to the list, edit existing hobbies, and remove them. Event handlers like handleHobbyValue, handleAddInput, handleHobbyEdit, and handleRemove manage these interactions.

Styling: Inline styles are used for simplicity, though using CSS classes would be cleaner.

React Rendering: React is rendered into the HTML element with the ID root.

Improvements:

1.Consolidate duplicate onClick handlers in the 'Add' button. 2.Extract inline styles into separate CSS classes for better maintainability. 3.1.Add input validation for better user experience.

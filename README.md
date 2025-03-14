# To-Do List Application

## Introduction
This is a simple To-Do List application built with React Native and Expo. The app allows users to add, edit, and delete goals dynamically while maintaining a structured and user-friendly interface.

## Features
### Basic Features:
- Users can enter a goal using a `TextInput` field.
- A button allows users to add goals to the list.
- Each goal item in the list has its own edit and delete button.
- Goals are displayed using a `FlatList` for efficient scrolling.

### Editing Mechanism:
- When clicking the "Edit" button, the selected goal becomes an editable `TextInput`.
- The user can modify the goal directly inside the item’s frame.
- A "Save" button appears, allowing the user to update the goal.

### Deleting Mechanism:
- Clicking the "Delete" button removes the goal from the list.

## Custom Fonts Implementation
To enhance the UI, the "Poppins" font was used for the application. The font was imported and applied to different text elements following Expo's official documentation ([Expo Fonts Guide](https://docs.expo.dev/develop/user-interface/fonts/)).

### Font Used:
- **Poppins** (Regular and Bold) , applied to titles, input fields, and list items.

## Design and Styling
- **Primary Background Color:** `#f5f5f5` (light gray for a clean look)
- **Text Color:** `#000000` (black for clear readability)
- **Input Field Background:** `#ffffff` (white for contrast)
- **Button Colors:**
  - Add Button: `#4caf50` (green for positive action)
  - Edit Button: `#4d79ff` (blue for modification action)
  - Delete Button: `#ff4d4d` (red for warning and removal)
- **List Items:** White background with rounded corners and subtle shadow.

## Screenshots
### Adding a Goal:
![Adding a Goal](screenshots/add%20goal1.png)
![Adding a Goal](screenshots/add%20goal2.png)

### Editing a Goal:
![Editing a Goal](screenshots/edit1.png)
![Adding a Goal](screenshots/edit2.png)

### Deleting a Goal:
![Deleting a Goal](screenshots/delete.png)

### Video:
![Demo](screenshots/gif%20demo.gif)

### Expo Snack link :
[expo link](https://snack.expo.dev/@ahmed_elwakad/to-do-list)

## Conclusion
This To-Do List application demonstrates effective state management and UI handling in React Native. The inclusion of inline editing enhances usability, making the app more efficient. Future improvements may include persistent storage using AsyncStorage to save tasks across sessions.


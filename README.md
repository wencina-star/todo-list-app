# ✓ Todo List Application

A modern, fully-functional todo list application with local storage. Built with vanilla HTML, CSS, and JavaScript.

## 🎯 Features

### Core Functionality
- ✅ Add Tasks - Create new tasks with a single click
- 📝 Edit Tasks - Modify existing tasks
- 🗑️ Delete Tasks - Remove individual tasks
- ✓ Mark Complete - Check off completed tasks
- 💾 Local Storage - All tasks automatically saved

### Priority System
- 🔴 High Priority - Urgent tasks (red)
- 🟠 Medium Priority - Standard tasks (orange) - Default
- 🟢 Low Priority - Less urgent tasks (green)

### Filtering & Search
- All - View all tasks
- Active - Show only incomplete tasks
- Completed - Show only finished tasks
- High Priority - Show only high priority tasks
- Search - Find tasks by keyword

### Statistics Dashboard
- Total number of tasks
- Number of completed tasks
- Number of pending tasks
- Real-time updates

### Additional Features
- 🎨 Modern, responsive design
- 📱 Mobile-friendly interface
- ⚡ Smooth animations
- 🌙 Purple gradient theme
- 🔄 Real-time filtering and search
- 📊 Live statistics

## 🚀 How to Use

### Adding a Task
1. Type your task in the input field
2. Select a priority level (optional, defaults to Medium)
3. Click "Add Task" or press Enter
4. Your task will appear at the top of the list

### Managing Tasks
- Complete - Check the checkbox next to a task
- Edit - Click the "Edit" button to modify the task
- Delete - Click the "Delete" button to remove the task

### Filtering
- Click the filter buttons to show different task categories
- Use the search bar to find specific tasks
- Filters work together with search

### Clearing Tasks
- Clear Completed - Removes all completed tasks
- Clear All - Removes all tasks permanently

## 💾 Data Persistence

All your tasks are automatically saved to your browser's Local Storage:
- Tasks persist even after closing the browser
- Tasks are stored locally (no internet connection needed)
- Clearing browser cache will delete all tasks
- Data is not shared with any server

## 🎨 Design Features

### Color Coding
- Purple Gradient - App theme and active states
- Green - Completed tasks indicator
- Red - Delete actions and high priority
- Orange - Medium priority
- Light gray - Inactive elements

### Responsive Design
- Desktop - Full layout with all features visible
- Tablet - Optimized spacing and touch targets
- Mobile - Stacked layout for single-column viewing

### Animations
- Smooth fade-in/fade-out transitions
- Slide-up animation on page load
- Slide-in animation for new tasks
- Hover effects on all interactive elements

## 📁 File Structure

```
.
├── index.html      # Main HTML file
├── styles.css      # All styling and animations
├── script.js       # Application logic
└── README.md       # Documentation
```

## 🔧 Technical Details

### Storage Format
Tasks are stored as JSON in Local Storage:
```json
[
  {
    "id": 1234567890,
    "text": "Task description",
    "completed": false,
    "priority": "medium",
    "createdAt": "2024-01-15T10:30:00.000Z"
  }
]
```

### Browser Compatibility
- Chrome ✅ Full support
- Firefox ✅ Full support
- Safari ✅ Full support
- Edge ✅ Full support
- Opera ✅ Full support

## 🛠️ Customization

### Change Theme Colors
Edit the CSS variables at the top of `styles.css`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    /* ... more colors ... */
}
```

## ⌨️ Keyboard Shortcuts
- Enter - Add new task (while in input field)

## 🐛 Troubleshooting

### Tasks disappeared
- Check if you cleared browser cache or local storage
- Different browsers have separate storage
- Private/Incognito mode doesn't persist data

### Tasks not saving
- Ensure browser allows local storage
- Check if you're in private/incognito mode
- Try a different browser

## 📝 Tips & Tricks

1. Use Priorities Wisely - High priority tasks stand out visually
2. Regular Cleanup - Clear completed tasks to keep the list manageable
3. Search Before Adding - Check if a task already exists
4. Edit Instead of Delete - When you make typos, use Edit
5. Use Different Filters - Switch between "Active" and "All" to focus

## 📱 Mobile Tips

- Tap the checkbox to quickly complete tasks
- Use the search feature to find tasks easily
- Use landscape mode for better visibility

## 🎓 Learning Resources

This project demonstrates:
- DOM manipulation with vanilla JavaScript
- Local Storage API
- Event handling and delegation
- CSS Grid and Flexbox
- Responsive design principles
- State management basics

---

**Start organizing your tasks today!** 🚀
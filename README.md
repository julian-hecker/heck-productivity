# Heck Productivity
Web-based suite of tools to increase personal productivity.

## Ideas
- https://amazingmarvin.com/features.html
    - nested projects, tasks, categories; subtasks
    - day planner
    - week planner
    - tree diagram, different visual tools
    - pomodoro
    - task time estimates, due date, end date, defer date
    - task dependencies
    - task notes
    - categorized GOAL ORGANIZATION
    - procrastination count
    - backburner / maybe
    - prioritization
    - kanban
    - calendar integration
    - urgent, important timescales
    - priorities
    - review, day notes
    - dashboard
    - reminders

## Todo
- Learn database of some sort, preferably MongoDB



```javascript
// pseudocode

  item.prototype = {
    uuid: #,
    name: '',
    description: '',
    notes: '',
    location: '',
    priority: #,
    dependencies: [],
    backburner: false,
  }

  Project.prototype = {
    // extends item
    tasks/children: [],
    category: '',
  }

  task.prototype = {
    // extends item
    duration: '5min',
    due: Date, 
    procrastination: // foreach day past due, +1 procrastination,
    reminder: {date, data},

  }
```




https://blog.amazingmarvin.com/three-simple-rules-writing-great-tasks-to-do-list/

https://blog.amazingmarvin.com/break-large-projects-tasks-bite-sized-tasks/

<img width="3420" height="2156" alt="buckets" src="https://github.com/user-attachments/assets/be257e57-cd9e-4f72-b7bc-b4f36e68c095" />

# Buckets

A simple prioritization tool with a retro Windows 95 twist. Built for people who want a no-fuss way to sort tasks by urgency and importance.

## Features

- **Eisenhower Matrix View** - Organize tasks by importance and urgency in a 2x2 grid
- **List View** - See tasks grouped by priority or complexity
- **Kanban Board** - Drag and drop tasks between columns
- **Drag & Drop** - Move tasks between quadrants/groups
- **Local Storage** - Your tasks persist in your browser
- **Export to CSV** - Download your tasks for backup or analysis
- **Retro Win95 UI** - Authentic Windows 95 styling for that nostalgic feel

## Usage

Just open `index.html` in your browser. No build step, no dependencies, no server required.

Or visit the live version at [jasonschulke.com/projects/buckets](https://jasonschulke.com/projects/buckets)

## How It Works

Tasks are categorized on two axes:
- **Priority** (High/Medium/Low) - How important is this task?
- **Complexity** (High/Medium/Low) - How much effort will it take?

The Matrix view maps these to an Eisenhower-style grid:
- **Do Now** - High priority, low complexity (quick wins)
- **Do Next** - High priority, high complexity (schedule these)
- **Do Later** - Low priority, low complexity (backlog)
- **Reconsider** - Low priority, high complexity (maybe skip these)

## Tech Stack

- Vanilla HTML/CSS/JavaScript
- Tailwind CSS (via CDN)
- Material Symbols icons
- No frameworks, no build tools

## License

MIT

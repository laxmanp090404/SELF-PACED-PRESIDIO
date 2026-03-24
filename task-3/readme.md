# Job Cards UI

## Overview

This is for representing the grid layout task

## Features

- **Responsive Grid Layout** - Adapts from 3 columns on desktop to 1 column on mobile
- **Job Card Components**:
  - Company logo display
  - Job title and posting timestamp
  - Employment type badges (Full-time, Part-time, Senior Level, etc.)
  - Hourly rate information
  - Job location
  - Apply Now action button

- **Interactive Elements**:
  - Hover effects with smooth scale animation
  - Stylized borders on hover
  - Professional button styling

- **Responsive Breakpoints**:
  - Desktop: 3-column grid (full width)
  - Tablet: 2-column grid (max-width: 1080px)
  - Mobile: 1-column layout (max-width: 768px)

## File Structure

```
task-3/
├── index.html      # Main htm
├── style.css       # style sheet for stylinh
├── readme.md       # task docs
└── assets/         # Company logos and icons
    ├── amazon.png
    ├── google.png
    ├── dribble.png
    └── save.png
```

## HTML Structure

Each job card contains three main sections:

1. **Top Section** - Company logo and save button
2. **Middle Section** - Company name, job title, posting time, and job type badges
3. **Bottom Section** - Salary, location, and apply button

## CSS Features

- **Card Styling**: Flexible card layout with smooth shadow and border effects
- **Grid System**: CSS Grid for responsive multi-column layout
- **Flexbox**: Used for component alignment and spacing
- **Transitions**: Smooth hover animations (scale, border animations)
- **Color Scheme**: Neutral grays with black action buttons and white text

## How to Use

1. Open `index.html` in a web browser
2. Browse through the job listings in the card grid
3. View responsive layout by resizing the browser window

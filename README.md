# Frontend Mentor - Notifications Page

A responsive notifications page built with HTML, CSS, and JavaScript, featuring dynamic rendering of notifications from data and interactive toggling of their visual state based on read status, as a solution to the [Frontend Mentor Notifications Page Challenge](https://www.frontendmentor.io/challenges/notifications-page-DqK5QAmKbC).

## Table of Contents

- [Overview](#overview)
  - [Features](#features)
  - [Desktop View](#desktop-view)
  - [Live Demo](#live-demo)
- [Technology Stack](#technology-stack)
- [How It Works](#how-it-works)
- [Learnings and Insights](#learnings-and-insights)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

---

## Overview

The Notifications Page is a user-friendly interface to display, manage, and mark notifications as read. It supports responsive layouts to provide optimal viewing across all devices.

### Features

- **Dynamic Interactivity**: Users can mark all notifications as read with a single click.
- **Unread Notifications Indicator**: Visual cues for unread notifications, including badges and background highlights.
- **Mobile and Desktop Friendly**: Responsive design ensures usability across devices.
- **Hover States**: Clear visual feedback for interactive elements.

---

#### Desktop View:

![Desktop View](https://github.com/user-attachments/assets/2b928d89-cf73-4927-95f0-ad01eec19919)

#### Mobile View:

![Mobile View](https://github.com/user-attachments/assets/ee3ed16f-2ee4-49bd-9698-389c9a1f770e)

### Links

- [Live Demo](https://gaping-rose.surge.sh/)

---

## Technology Stack

- **HTML5**: Semantic markup for accessibility and SEO.
- **Tailwind CSS**: Utility-first framework for styling.
- **JavaScript (ES6)**: Interactive functionality.
- **Google Fonts**: Custom typography using "Plus Jakarta Sans".

---

## How It Works

1. Notifications are visually differentiated as unread (highlighted) or read.
2. The "Mark all as read" button dynamically updates the interface, removing badges and setting the unread count to zero.
3. Hover states provide intuitive feedback, enhancing user engagement.

Key functions:

- **handleSubmit(event)**: Handles the "Mark all as read" button click.
- **markRead()**: Toggles the visual state of unread notifications, updates the count, and removes highlights.

---

## Learnings and Insights

- Gained hands-on experience with **Tailwind CSS** for rapid UI development.
- Improved understanding of **DOM manipulation** and JavaScript event handling.
- Practiced responsive design principles to ensure cross-device compatibility.

---

## Author

- GitHub - [@sayaliakbar](https://github.com/sayaliakbar)
- LinkedIn - [@sayaliakbar](https://linkedin.com/in/sayaliakbar)

---

## Acknowledgments

- Challenge provided by [Frontend Mentor](https://www.frontendmentor.io).
- Inspired by the interactive UI designs of modern web applications.

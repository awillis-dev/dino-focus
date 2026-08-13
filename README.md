# dino-focus

# Dino Focus

A lightweight focus and task-timer app that pulls tasks live from Todoist,
runs Pomodoro-style timers per task, and keeps a permanent log of what
you've finished.

## Features

- **Live Todoist sync** — connect a personal Todoist API token and pull
  today's due/overdue tasks directly into the app. Marking a task done
  here closes it in Todoist too.
- **Focus timer** — start a countdown for any task, with a circular
  progress ring, pause/resume, +/-5 min adjustments, and an optional
  chime when time's up. Pop it out into a small floating timer or a
  Picture-in-Picture window so it stays visible while you work elsewhere.
- **Now / Not now / Done** — a simple three-column flow to keep today's
  list from feeling overwhelming, with drag-to-reorder in "Now."
- **All-time history** — every completed task is archived permanently,
  separate from today's list, so you can look back over what you've
  gotten done.
- **Light/dark theme** and a "top 3 only" focus view for cutting down
  visual noise.

## Setup

1. Open the app (via GitHub Pages, or locally in a browser).
2. Click the 🔗 icon and paste a Todoist personal API token
   (found at Todoist → Settings → Integrations → Developer).
3. Click **Sync with Todoist** to pull in today's tasks.

Your token and task data are stored only in your browser's local
storage — nothing is sent anywhere except directly to Todoist's API,
and nothing is ever committed to this repo.

## Live demo

[Add your GitHub Pages URL here once it's live]

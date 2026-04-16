# JavaScript-Gantt

A lightweight browser demo showing a Gantt chart rendered with Syncfusion EJ2.

## Overview

This repository contains a single HTML example that renders a Gantt chart using Syncfusion's `ej2` library. The demo shows hierarchical task structure, task dates, durations, progress, and weekend highlighting.

## Files

- `SimpleGantt.html` — main demo file that initializes the Gantt chart and renders it in the browser.

## Features

- parent and child tasks
- task start date, duration, and progress tracking
- left-side task labels
- weekend highlighting
- fixed project start and end dates

## Usage

1. Open `SimpleGantt.html` in a web browser.
2. The page loads Syncfusion EJ2 scripts and styles from CDN.
3. The chart renders in the `#Gantt` container.

## Running Locally

No build tools required. Open the HTML directly or run a local server:

- Python 3: `python -m http.server 8000`
- Node.js: `npx http-server .`

Then visit `http://localhost:8000/SimpleGantt.html`.

## Customization

Edit the `GanttData` array in `SimpleGantt.html` to change tasks, dates, durations, progress, and hierarchy. You can also update `taskFields`, `labelSettings`, and the project date range.

## Notes

The demo uses CDN-hosted Syncfusion resources:

- `https://cdn.syncfusion.com/ej2/17.3.9-beta/dist/ej2.min.js`
- `https://cdn.syncfusion.com/ej2/material.css`

For production use, consider managing dependencies locally or with a bundler.

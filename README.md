# Job Application Tracker

A simple, responsive job application tracker built with HTML, Tailwind CSS, and vanilla JavaScript. This project helps users view a list of job opportunities, filter applications by status, update job statuses, and remove jobs from the list.

## Features

- View a list of available job opportunities
- Filter jobs by status:
  - All
  - Interview
  - Rejected
- Update job status directly from each card
- Delete job cards from the list
- Automatically updated summary counts
- Empty state display when no jobs match the selected filter
- Responsive layout for desktop and mobile screens
![alt text](<Screenshot (25)-1.png>) ![alt text](<Screenshot (26)-1.png>) ![alt text](<Screenshot (27)-1.png>) ![alt text](<Screenshot (28)-1.png>) ![alt text](<Screenshot (29)-1.png>) ![alt text](<Screenshot (30)-1.png>)
## Tech Stack

- **HTML5** — page structure
- **Tailwind CSS** — styling and layout
- **JavaScript (Vanilla)** — DOM manipulation and interactivity
- **Font Awesome** — trash icon
- **Google Fonts (Geist)** — typography

## Project Structure

```text
├── index.html
├── script.js
├── README.md
├── jobs.png
├── Job Application Tracker.fig
└── tailwind.config.js
```

## How It Works

### Job Cards
Each job card displays:

- Company name
- Role title
- Location, job type, and salary
- Short description
- Current application status

### Filtering
The filter buttons at the top let you switch between:

- **All** jobs
- Jobs marked as **Interview**
- Jobs marked as **Rejected**

The available jobs count updates automatically based on the active filter.

### Status Updates
Each card includes status buttons that allow you to mark the job as:

- **Interview**
- **Rejected**

When a status changes, the summary counters update immediately.

### Delete Job
Click the trash icon on a job card to remove it from the list.

## Getting Started

### 1. Clone or download the project

```bash
git clone <repository-url>
```

### 2. Open the project

This is a static frontend project, so no installation is required.

Open `index.html` directly in your browser, or use a local development server.

### 3. Run locally with a simple server

If you want to serve it locally, you can use any static server. For example:

```bash
npx serve
```

or

```bash
python -m http.server 8000
```

Then open the displayed local URL in your browser.

## Usage

1. Open the page in a browser.
2. Review the job cards and summary counters.
3. Use the filter buttons to view specific application statuses.
4. Click **INTERVIEW** or **REJECTED** to update a job’s status.
5. Click the trash icon to remove a job card.
6. When no jobs match the active filter, the empty state will appear.

## Notes

- The current job listings are hardcoded in `index.html`.
- The app uses DOM manipulation to update filters, counters, and statuses in real time.
- `tailwind.config.js` is currently empty because styling is handled through the Tailwind CDN in `index.html`.

## Future Improvements

- Add a form to create new job applications
- Persist data using `localStorage`
- Add an edit job modal
- Support more application statuses
- Replace hardcoded data with dynamic JSON or API-driven content

## License

This project does not currently include a license. Add one if you plan to share or publish it publicly.

## Screenshots

1. ![Screenshot 25](Images/Screenshot%20%2825%29.png)
2. ![Screenshot 26](Images/Screenshot%20%2826%29.png)
3. ![Screenshot 27](Images/Screenshot%20%2827%29.png)
4. ![Screenshot 28](Images/Screenshot%20%2828%29.png)
5. ![Screenshot 29](Images/Screenshot%20%2829%29.png)
6. ![Screenshot 30](Images/Screenshot%20%2830%29.png)

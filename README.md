# GateOS 2026: Your Ultimate GATE Exam Manager

**GateOS 2026** is a state-of-the-art, single-file web application designed to help you meticulously track and manage your preparation for the GATE 2026 examination in both Data Science & Artificial Intelligence (DA) and Electrical Engineering (EE).

With a focus on efficiency and clarity, GateOS provides a personalized dashboard to visualize your progress, prioritize key topics, and stay on track for the February 10, 2026 deadline.

## Features

*   **Dual Syllabus Tracking:** Comprehensive listing of all topics from both DA and EE syllabi.
*   **Smart Prioritization:** Topics are categorized into High, Mid, and Low priority based on detailed analysis, ensuring you focus on high-yield areas.
*   **Overlap Zone:** A dedicated section for common topics between DA and EE. Progress here automatically syncs across both subject lists, maximizing your study efficiency.
*   **Real-time Progress Circles:** Visual indicators on the dashboard show your completion percentage for each paper (DA and EE) independently.
*   **High-Priority Completion:** Track your progress specifically on critical, high-priority topics.
*   **Velocity Tracker:** Calculates the number of topics you need to cover per day to meet your February 10, 2026 deadline.
*   **Local Data Persistence:** All your progress is saved directly in your browser (using `localStorage`), ensuring your data is always available without any backend or account creation.
*   **Clean & Responsive UI:** An intuitive, dark-themed interface optimized for a focused study experience.
*   **Zero-Dependency:** The entire application is contained within a single `index.html` (or `gate_dashboard.html`) file. No installation of Node.js, Python, or any other tools is required to run it.

## How to Use

1.  **Open the File:** Simply open the `gate_dashboard.html` file in any modern web browser (e.g., Google Chrome, Firefox, Edge).
2.  **Navigate:** Use the sidebar to switch between "Mission Control" (dashboard), "Overlap Zone," "DA Syllabus," and "EE Syllabus."
3.  **Track Progress:** Click the checkboxes next to each topic as you complete them. Your progress will automatically update on the dashboard and in relevant sections.
4.  **Overlap Sync:** Mark topics in the "Overlap Zone" to have them automatically marked in both DA and EE syllabi.
5.  **Reset Progress:** If you wish to clear all your saved progress and start fresh, click the "Reset Data" button in the sidebar.

## Deployment (Vercel Ready)

**GateOS 2026** is designed for effortless deployment as a static site.

To deploy it to platforms like Vercel:

1.  **Clone this repository** (or download `gate_dashboard.html`).
2.  **Create a new project on Vercel.**
3.  **Import your repository.**
4.  **Vercel will automatically detect the `gate_dashboard.html` file** and deploy it as a static website. No special build commands or configurations are needed.

Your personal GATE manager will be live and accessible from anywhere!

## Development Notes

*   The syllabus data is hardcoded within the `gate_dashboard.html` file for simplicity and zero-dependency. If you need to update the syllabus, you would edit the `syllabusData` JavaScript object directly within the `html` content. (Previously, a Python script was used to generate this HTML, but for a single-file, deployable solution, the HTML is now self-contained).
*   Progress is saved using `localStorage` with the key `gate_os_v3_progress`.

---

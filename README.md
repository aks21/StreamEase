# Progressive Web Application (PWA)

Welcome!!! This project is a demonstration of a Progressive Web Application (PWA) that offers a native app-like experience with full offline capabilities and persistent storage. The goal of this project is to provide a clear example of how to build a PWA that can handle media playback and downloads, all while being responsive and user-friendly.

## Features

- **Media Playback**: Supports various media types, including audio and video. 
- **Media Download**: Allows users to download media files. The app uses the Fetch API to download files as blobs, which are then stored in IndexedDB for offline access.
- **IndexedDB Storage**: Utilizes IndexedDB for client-side storage of significant amounts of structured data, including downloaded media files, for persistent offline access.
- **Progress Bar**: Includes a visual progress bar at the top of the page to indicate the progress of file downloads, which disappears after completion or a set delay.
- **Manifest and Service Worker**: Features a `manifest.json` file for app metadata and a service worker for offline functionality and fast loading, even on unreliable networks.
- **Responsive Design**: Crafted with a responsive layout and styles to ensure a seamless user experience across various devices and screen sizes.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- A modern web browser that supports PWAs
- Basic knowledge of HTML, CSS, and JavaScript.
- A code editor of your choice (e.g., Visual Studio Code, Sublime Text)


Usage
To use the app, simply navigate to the hosted URL or run it locally. You can play media files, download them for offline use, and enjoy a fully responsive PWA experience.

### Installation

1. Clone the repository:

```bash
git clone given project-name
cd given project-name
npm install
npm start

The app should now be running on http://localhost:3000. Simply navigate to the hosted URL or run it locally.

# Text-Editor

## Overview
This is a text editor web application that provides a client-server architecture, webpack bundling, IndexedDB for content storage, and service worker integration using Workbox.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) - Ensure that Node.js is installed on your machine.

### Installation

1. Clone the repository:

    git clone git@github.com:Clarisagonzalez/Text-Editor.git
    

2. Navigate to the project directory:

    cd your-repo

3. Install dependencies:

    npm install
    

### Running the Application

To start the application (both backend and client), run:

npm run start

### Feature
Webpack Bundling: JavaScript files are bundled using Webpack to optimize the application.

IndexedDB Integration: IndexedDB is used for immediate database storage when the text editor is opened.

Content Persistence: Entered content is saved in IndexedDB when clicking off the DOM window, and it is retrieved upon reopening the text editor.

Service Worker and Workbox: The application includes a registered service worker using Workbox for offline capabilities and static asset caching.

Desktop Installation: The "Install" button allows users to download the web application as an icon on their desktop.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

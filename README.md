# Frontend in Orbit

Frontend in Orbit is the user interface component of the **Server in Orbit** project, designed to provide a smooth and interactive experience for monitoring and managing space-bound servers.

## Features

- **Real-time Data**: Displays live updates from the server using WebSocket connections.
- **Interactive UI**: User-friendly dashboard for easy access to system statistics and controls.
- **Responsive Design**: Optimized for mobile, tablet, and desktop.

## Technologies Used

- **React**: Core UI framework for building the frontend.
- **Tailwind CSS**: Utility-first CSS framework for fast styling.
- **WebSocket**: Real-time communication with the backend.
- **Vite**: Blazing fast development environment.

## Getting Started

Follow these steps to get the frontend running locally or in a production environment.

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/en/)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:

    \`\`\`bash
    git clone https://github.com/maia2a/frontend-in-orbit.git
    \`\`\`

2. Navigate into the project directory:

    \`\`\`bash
    cd frontend-in-orbit
    \`\`\`

3. Install dependencies:

    \`\`\`bash
    npm install
    \`\`\`

### Running the Application

#### Development Mode

To run the app in development mode:

\`\`\`bash
npm run dev
\`\`\`

Visit [http://localhost:3000](http://localhost:3000) to view the app.

#### Production Build

To build the app for production:

\`\`\`bash
npm run build
\`\`\`

The production files will be generated in the \`dist\` folder.

### WebSocket Communication

The frontend communicates with the backend server via WebSockets. Ensure the server is running and accessible at \`ws://localhost:3000\` to receive real-time updates.

### Configuration

You can modify environment variables in the \`.env\` file to configure the app:

- \`VITE_API_URL\`: Set the API URL for backend communication.
- \`VITE_WEBSOCKET_URL\`: Set the WebSocket URL for real-time updates.

### Deployment

To deploy the app:

1. Build the production files:

    \`\`\`bash
    npm run build
    \`\`\`

2. Serve the static files using a web server or host them on a platform like Vercel or Netlify.

## Contributing

Feel free to submit pull requests or issues to improve the project. All contributions are welcome!
"""

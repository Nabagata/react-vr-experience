# React VR Experience

An immersive React-based VR web experience built with Three.js and the WebVR API.

## Project Overview

`react-vr-experience` demonstrates a modern VR-enabled web application using React 18 and Three.js. It provides an immersive 360-degree environment viewable in VR headsets or browsers with VR support.

## Requirements

- Node.js >= 18.0.0
- npm >= 9.0.0

## Installation

```bash
npm install
```

## Running the Project

```bash
npm start
```

The application will start on `http://localhost:1234`

## Development

### Project Structure

- `index.js` - Main React component with VR UI
- `app.js` - Express server for serving the built application
- `client.js` - Client-side initialization
- `index.html` - HTML entry point
- `static_assets/` - VR assets and media files

### Testing

```bash
npm test
```

## Technology Stack

- **React 18** - UI library
- **Three.js 0.159** - 3D graphics engine
- **Express 4.18** - Web server
- **WebVR Polyfill** - VR API polyfill for browser compatibility

## Security

All dependencies are regularly updated to address security vulnerabilities. Last security audit: August 28, 2026 - **0 vulnerabilities found**.

## License

Private - Personal Project

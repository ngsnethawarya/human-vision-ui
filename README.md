# Human Vision UI

A small Angular-based UI for experimenting with **face image capture** and testing **biometric API interactions** during development.

> **Note:** This is an experimental/dev tool. It is not intended for production use.


## What this project does

Human Vision UI provides a simple browser interface to:

- Capture a face image from a webcam (or upload an image, if you add that flow)
- Preview the captured image before sending
- Send the image payload to a backend biometric service for testing workflows (enroll/verify/identify, etc.)
- Quickly iterate UI ideas while your backend/API is still changing


## Tech stack

- Angular (UI)
- TypeScript
- Browser Media APIs (getUserMedia) for webcam capture
- HTTP client for backend API calls


## Getting started

### Prerequisites

- Node.js (LTS recommended)
- npm (or yarn)
- Angular CLI (optional, but helpful)

### Install

```bash
git clone https://github.com/ngsnethawarya/human-vision-ui.git
cd human-vision-ui
npm install

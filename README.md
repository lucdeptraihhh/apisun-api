# apisun Render

Node.js/Express API for Render.

## Deploy
1. Upload this folder to a GitHub repository.
2. In Render, choose **New + → Blueprint** and select the repository, or create a Web Service.
3. Build command: `npm install`
4. Start command: `npm start`
5. Render supplies `PORT` automatically.

## Endpoints
- `/`
- `/health`
- `/taixiu`
- `/api/his`
- `/api/models`

The server binds to `0.0.0.0` so Render can expose it publicly.

> Keep any WebSocket/API credentials in Render Environment Variables/Secrets rather than committing them to Git.

# Random Meet

Arabic RTL random text chat built with Node.js, Express, and Socket.IO.

## Run locally

Requirements: Node.js 18 or newer.

```bash
npm install
npm start
```

Open `http://localhost:3000`.

## Deploy to a Node.js host (example: Render)

1. Upload the contents of this folder to a GitHub repository (the `package.json`, `server.js`, `public/` folder, and this README should be at the repository root).
2. On Render, create a **New Web Service** and connect that GitHub repository.
3. Set **Build Command** to `npm install` and **Start Command** to `npm start`.
4. Deploy, wait for the build to finish, then open the public URL Render provides.

The server listens on `process.env.PORT`, as required by common Node.js hosts.

## Important limitations

- Matching and online counts are real for users connected to the same running server instance.
- Block lists and reports are held in memory and are lost when the server restarts. Reports are not sent to a moderation team.
- This is a starter project, not a fully moderated dating service. Add persistent storage, stronger abuse prevention, and a real moderation workflow before promoting it publicly.
- Use only for adults 18+. Do not share personal contact details with strangers.

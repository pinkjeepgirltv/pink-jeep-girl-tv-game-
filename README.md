# Pink Jeep Girl TV — Dream City LIVE

An original multiplayer browser game for up to 8 players. The host creates a room; players join from phones using a room code or invitation URL. Turn-based dice, virtual properties, Pink Dollars, surprise cards, and leaderboard. No gambling or real-money features.

## Run locally

Install Node.js 18 or newer, then in this folder run:

```bash
npm install
npm start
```

Open http://localhost:3000 on your computer. For viewers on different networks, deploy the app to a Node.js web host (for example, Render or Railway). A static-only host will **not** work because this game needs a live Socket.IO server.

## Deploy on Render (example)

1. Put the files in a GitHub repository (keep the `public` folder).
2. Create a new Render **Web Service** connected to that repository.
3. Build command: `npm install`.
4. Start command: `npm start`.
5. Use the public HTTPS URL that Render assigns. Open it, select **Host a game**, and share the displayed invite URL or five-character room code.

The host should keep the game tab open. Rooms exist in server memory and reset if the server restarts. Free-tier hosts may sleep or have usage limitations. This starter is intended for casual play, not large public events. There are no persistent accounts, reconnect recovery, moderation tools, or real-time TikTok-comment integration. Do not share private information in player names.

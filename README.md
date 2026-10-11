# Musify

Musify is a Spotify-inspired music streaming project with a customer-facing web app, an admin dashboard, and an Express API.

## Project structure

- `spotify-clone/` - React and Vite customer app
- `spotify-admin/` - React and Vite admin dashboard
- `spotify-backend/` - Express API, MongoDB, and Cloudinary integration

## Requirements

- Node.js and npm
- A MongoDB connection string
- Cloudinary credentials for backend media uploads

## Configure the backend

In `spotify-backend/`, copy `.env.example` to `.env` and fill in your own credentials. Do not commit `.env`.

## Run locally

Start each service in a separate terminal from the project root:

```powershell
cd spotify-backend
npm install
npm run server
```

```powershell
cd spotify-clone
npm install
npm run dev
```

```powershell
cd spotify-admin
npm install
npm run dev
```

The API runs on port `4000`. Vite prints the local URLs for both frontends when they start (usually ports `5173` and `5174`).

# Walkers World TV Monitor — Full Build v2

YouTube growth dashboard for Walkers World TV.

Includes Google OAuth, YouTube Data API, YouTube Analytics API, automatic monitoring, persistent snapshots, alerts, recent-video analysis, comment mining, trend radar, growth recommendations, and ready-to-copy video prompts.

## Run
1. Create .env from .env.example
2. Add Google OAuth credentials
3. Set BASE_URL to the deployed HTTPS URL
4. npm test
5. npm start

Google OAuth callback:
BASE_URL/auth/youtube/callback

Never commit .env or your Google Client Secret.

SETUP:

1. Install Node.js:
https://nodejs.org

2. Open this folder in Command Prompt

3. Run:
npm install

4. Rename ".env.example" to ".env"

5. Set up credentials:

Twitch:
https://twitchtokengenerator.com/
- Click "Bot Chat Token"
- Log in with Twitch
- Copy the token
- Paste into TWITCH_OAUTH in the .env file
  (Make sure it starts with: oauth:)

Spotify:
https://developer.spotify.com/dashboard
- Create a new app
- Copy Client ID and Client Secret
- Add Redirect URI:
  http://127.0.0.1:8888/callback
- Paste values into the .env file

6. Run:
node bot.js

7. Open in browser:
http://127.0.0.1:8888/login

8. Log into Spotify and approve

DONE

COMMAND:
!sr song - artist

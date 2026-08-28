# My Weather — Android-friendly web app

## Quick start

1. Put these files on a web host (GitHub Pages, Cloudflare Pages, Netlify, or another static host).
2. Open the site on your Android phone.
3. Enter your OpenWeather API key and press **Save & Load Weather**.
4. Choose a city or use **Use my location**.
5. The page refreshes automatically every **15 minutes**.

You can then use Chrome's **Add to Home screen / Install app** option to make it behave like an app.

## API key

The key is entered in the app and stored in the browser's localStorage. It is not sent anywhere except OpenWeather.

For a public production app, a backend/proxy is preferable because a browser-based app necessarily exposes the API key to the user.

## Files

- `index.html` — complete app
- `manifest.json` — makes it installable as a PWA

The app uses OpenWeather's Current Weather API and 5-day/3-hour Forecast API with metric units.

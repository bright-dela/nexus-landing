# Nexus API Landing Page

Landing page for the Nexus E-Commerce API.

## Local Development

Simply open `index.html` in a browser or use a local server:
```bash
python -m http.server 8080
```

Then visit: http://localhost:8080

## Deployment

This site is automatically deployed to Netlify on every push to main branch.

## Configuration

Update the `API_URL` in `index.html` to point to your backend:
```javascript
const API_URL = 'https://your-app-name.onrender.com';
```
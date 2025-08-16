# Trafik

A Chrome extension that intercepts and overrides network requests, making it easy to mock responses and debug APIs in real time.

## What it does

Trafik allows developers to:
- Intercept network requests in the browser
- Override responses with custom data
- Mock API endpoints for testing and development
- Debug network issues in real-time

## Getting Started

1. Clone this repository
2. Install dependencies: `npm install`
3. Build the extension: `npm run build`
4. Load the extension in Chrome:
   - Open Chrome and go to `chrome://extensions/`
   - Enable "Developer mode"
   - Click "Load unpacked" and select the `dist` folder

## Development

- `npm run dev` - Start development mode
- `npm run build` - Build for production
- `npm run watch` - Watch for changes

## Project Structure

```
trafik/
├── assets/          # Extension assets
├── popup.tsx        # Extension popup UI
├── package.json     # Dependencies and scripts
└── tailwind.config.js # Tailwind CSS configuration
```

## License

MIT

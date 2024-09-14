## Setup

Open a terminal and navigate to the root of this repo. Run

```
npm install
```

Open VSCode and installed the recommended extensions. You might need to restart VSCode in order for extensions to take in effect. Restart by running `CMD+Shift+P` and search for "Reload Window", hit `Enter`.

## Run Dev Environment

```
npm run dev
```

Navigate to http://localhost:5173/

## Deploy to GH-Pages

**It is important that you follow these steps in the correct order:**

1. Add `"homepage": "https://<user|org>.github.io/<repo>/"` to `package.json`
2. Push to GH
3. Wait until action finishes, this will create a new branch `gh-pages`
4. In your GH repo: Settings -> Pages -> Build and deployment -> Branch -> gh-pages

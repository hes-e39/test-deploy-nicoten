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

1. Open `package.json` and update the `"homepage"` key with your repo information. It should change from:

`"homepage": "https://hes-e39.github.io/react-ts-template/"`

to

`"homepage": "https://hes-e39.github.io/<your repo>/"`

For this assignment, the repo name will be `test-deploy-<your username>`.

Make sure the trailing `/` is there!

2. Push changes to GH
3. Wait until actions finish, this will create a new branch `gh-pages` and run the deployment
4. In your GH repo: Settings -> Pages -> Build and deployment -> Branch -> gh-pages

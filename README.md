# DJ Suman Website

A self-contained static website preview. The `assets` folder must stay beside `index.html` so photos and videos load.

## Run the site

- Open this folder in Visual Studio Code.
- In the VS Code terminal, run `npm run dev`.
- Open `http://localhost:5173` in your browser. The local server serves the images and videos and supports video seeking.
- Stop the server with `Ctrl+C` in the terminal.

No `npm install` is needed; the preview server uses Node.js built-ins only.

## Publish to GitHub from VS Code

1. Sign in to GitHub in VS Code (Accounts icon at the lower left).
2. Open **Source Control** and choose **Publish to GitHub**.
3. Name the repository `dj-suman-website` and choose **Private** unless you want the source to be public.
4. Confirm publishing. The HTML, images and video assets will be uploaded with the project.

This is a front-end preview. The date form does not check a live calendar or send enquiries until connected to a booking service.

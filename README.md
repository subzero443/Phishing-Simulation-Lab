# Phishing Simulation Lab

A local-first cybersecurity awareness dashboard built with React, TypeScript, Vite, and Tailwind CSS. It includes synthetic campaign data, safe message templates, campaign analytics, an awareness-training preview, and client-side email-header and URL analyzers.

# Screenshots
<img src="Screenshot 2026-10-05 015018.png">
<img src="Screenshot 2026-10-05 014808.png">
<img src="Screenshot 2026-10-05 014833.png">
<img src="Screenshot 2026-10-05 015221.png">

## Requirements

- Node.js 20.19+ or 22.12+
- npm (included with Node.js)
- Git, if you are cloning the repository.

1. Open a terminal in the project folder or In Windows Powershell running as An Administrator

Type the First command:
```bash
cd "C:\Users\INVESTOR\Desktop\Phishing Simulation Lab"
````
Replace INVESTORR with your PC User Name

2. Install the dependencies:
```bash
  npm install
```
3. Start the development server:
 ```bash
  npm run dev
```


5. Open the local URL printed in the terminal. By default, Vite uses `http://localhost:5173/`.

Press `Ctrl+C` in the terminal to stop the server.

## Other Commands

Create a production build:

```bash
npm run build
```

Serve the production build locally:

```bash
npm run preview
```

Run the linter:

```bash
npm run lint
```

## Safety and Project Scope

- Campaigns and analytics use sample data; campaign changes exist only in browser memory and reset when the page is reloaded.
- The campaign flow creates drafts only. The project does not send email, use tracking pixels, or collect credentials.
- The email analyzer parses pasted headers in the browser. The URL analyzer inspects URL structure without opening or contacting the destination.
- This version is a frontend prototype. It does not include a FastAPI backend, database, authentication, or persistent campaign storage.

Use only email headers and URLs that you own or are authorized to analyze. Analyzer results are heuristic and do not establish that a message or URL is safe.

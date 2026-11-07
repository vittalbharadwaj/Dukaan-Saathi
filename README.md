# Dukaan Saathi — The AI Munshi for Kirana Stores

Dukaan Saathi is a concept prototype for a voice-first AI assistant designed to help India's kirana store owners manage everyday shop operations in their own language.

## What the prototype demonstrates

- **Voice-first interaction concept:** Sample conversations in Hindi, Kannada, Tamil and English.
- **Shop economics calculator:** An illustrative model for estimating revenue potentially recovered from stock-outs.
- **Shelf inventory demo:** Simulated stock levels and reorder alerts.
- **System architecture concept:** A visual overview of a possible Google AI and Google Cloud architecture.

## Important prototype limitations

This repository contains a **front-end demonstration only**. The voice conversation, shelf scan, stock figures and reorder flow are simulated in the browser. It does not currently connect to a live AI model, camera-based inventory system, database, WhatsApp, distributor, UPI or billing system.

The revenue calculator is illustrative, not a measured business result. Validate assumptions with real kirana stores before using them in business or investor materials.

## Run locally

No build step or package installation is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

For a local web server, you can also run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub

1. Create a new repository on GitHub, for example `dukaan-saathi`.
2. Upload the files in this project, keeping `index.html` at the repository root.
3. Commit the files to the `main` branch.

## Deploy to Vercel

1. Sign in to [Vercel](https://vercel.com/).
2. Choose **Add New → Project**.
3. Import your `dukaan-saathi` GitHub repository.
4. For this static HTML project, leave the framework preset as **Other**.
5. Leave the build command and output directory empty; the site is served from the repository root.
6. Click **Deploy**.

Vercel can redeploy the site automatically whenever you push changes to the connected GitHub repository.

## Suggested next development steps

1. Validate the workflow with kirana owners and document their feedback.
2. Add a secure backend and database for real inventory, sales and customer ledgers.
3. Integrate speech recognition and an AI service through server-side API routes. Keep API keys out of browser code and GitHub.
4. Build and test real camera-based inventory recognition.
5. Add distributor ordering only after confirmation, with clear approval and audit history.
6. Add authentication, authorization, privacy controls, backups and monitoring before handling real shop data.

## Project status

Early-stage concept / interactive front-end prototype.

## License

No license has been specified yet. Add a license file before inviting external reuse or contributions if you want to define how others may use the code.

# Codexa Technologies developer website

A lightweight, responsive website for Codexa Technologies and Hangman: Word Quest. The site uses plain HTML and inline CSS, with no build step, scripts, tracking, or external dependencies.

## Files

- index.html: the developer homepage, game introduction, contact details, and links to the existing privacy policy.
- app-ads.txt: the authorized AdMob seller entry, served from the domain root.

The privacy policy is maintained separately. This repository only links to it.

## Publish with GitHub Pages

Repository: https://github.com/Dhanush-18-hub/dhanush-18-hub.github.io

In repository **Settings > Pages > Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then **Save**. No custom domain is needed.

After Pages is configured, push website changes to main and wait for GitHub's Pages deployment to finish. Confirm these URLs return successfully:

- Homepage: https://dhanush-18-hub.github.io/
- Seller file: https://dhanush-18-hub.github.io/app-ads.txt
- Existing privacy policy: https://dhanush-18-hub.github.io/hangman-word-quest-privacy/

Keep app-ads.txt as a plain-text file in the repository root, containing only the supplied seller entry. Do not change its publisher ID or add HTML.

## Preview locally

From this repository, run:

    python -m http.server 8000 --bind 127.0.0.1

Open http://127.0.0.1:8000/ and stop the server with Ctrl+C when finished.

## AdMob verification

Publishing the website and seller file does not by itself confirm AdMob verification. Set the developer website in the app's Google Play store listing to https://dhanush-18-hub.github.io/ and then check the app-ads.txt status in AdMob.

Google's instructions: https://support.google.com/admob/answer/9363762

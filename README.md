# Flex Signal Lab

Mobile-first manual signal prototype for manually entered prices from an Olymptrade Flex chart.

## Safety and limitations
- Rule-based technical prototype, not a trained AI model.
- Does not log in, connect to Olymptrade, scrape the platform, or place trades.
- No verified live data feed for Asia Composite Index.
- Signals are not financial advice or probabilities of success.

## Use on iPhone
1. Open `index.html` in a browser or publish with GitHub Pages.
2. Enter recent prices oldest-to-newest, separated by commas.
3. Tap Analyze prices and later record the observed expiry price in the paper-trade section.

## Publish with GitHub Pages
1. Upload `index.html` and `README.md` to your repository.
2. Open Settings → Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Select `main` and `/(root)`, then Save.
5. Wait for GitHub Pages to publish the page.

GitHub Pages hosts the static interface only. It does not run a continuous trading process or provide live market data.

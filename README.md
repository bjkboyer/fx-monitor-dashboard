# FX Monitor Dashboard

A single-file trading dashboard for the FX Monitor system — trade signal review, OANDA reconciliation, F-indicator analytics, and live position tracking.

## Live feed setup

This dashboard reads from an n8n webhook that publishes a combined snapshot of OANDA transactions and Google Sheets trade signal data. Click **Connect live feed** in the app and paste your n8n webhook URL.

No credentials are ever stored or transmitted by this dashboard — it only reads the public JSON snapshot your n8n workflow publishes.

## Installing as an app

On a phone, open this page in your browser and choose **Add to Home Screen** (iOS Safari) or **Install app** (Android Chrome) to use it like a native app, with offline shell loading.

## Data and privacy

All trade data is stored locally in your browser (`localStorage`) and is never sent anywhere except the n8n webhook you configure.

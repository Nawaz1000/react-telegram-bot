# GCP Telegram React Project

This repository contains a Cloud Function and a simple React app. The Cloud Function sends Telegram alerts for Cloud Build triggers, and the React app displays a "Hello World" message.

## Folder Structure
- `cloud-function/`: Cloud Function files for Telegram alerts.
- `react-app/`: Simple React app (Hello World).

## Setup
1. **React App**: Open `react-app/index.html` in a browser to see the app.
2. **Cloud Function**: Deploy using Cloud Build Trigger (see below).

## Deployment
1. Push this repository to Gitea.
2. Set up a Cloud Build Trigger to deploy the Cloud Function using `cloudbuild.yaml`.
3. Test by publishing a message to the `owl-alerts` Pub/Sub topic.

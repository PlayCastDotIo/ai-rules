# Ruleset: Analytics

- Use PowerShell syntax for all CLI steps.
- Environment: Windows 11, GCP (Cloud Functions v2, BigQuery), Amplitude.
- Events originate from React or Node applications.
- Route through GA4 or directly to BigQuery.
- Process events in BigQuery using SQL.
- Forward processed events to Amplitude for reporting.
- Use gcloud CLI over the console unless simplicity is a priority.
- Prefer Eventarc-based Pub/Sub triggers for authenticated ingestion.

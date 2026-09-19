# User Sage Status

Public uptime and incident status for User Sage.

This repo is the operational home for the public status page and uptime monitoring. It is intentionally separate from the app repo so deploy safety and status communication can evolve independently.

## Intended use

- status page for `status.usersage.com`
- uptime checks for app, API, auth, and AI endpoints
- incident timeline and component status
- deploy safety and downtime communication

## Repo split

- `user-sage-app` handles runtime deploy maintenance mode
- `user-sage-status` handles public status visibility and monitor setup

## Recommended next step

Use this repo with a hosted status solution or Upptime-style workflow to publish the public status page, then bind the custom domain.

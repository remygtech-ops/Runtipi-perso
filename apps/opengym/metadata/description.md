# openGym

A self-hosted gym and body-weight tracker you actually own. No subscription, no ads, no telemetry.

## Features

- A routine per weekday over **5,600+ exercises** with animated demos
- Guided workouts: log every set, supersets and cardio included
- Body-weight tracking, stats, heatmap and personal records
- Installable on your phone (PWA), works offline and syncs between devices
- Passkey sign-in, optional admin dashboard and invite codes

## Important: passkeys need HTTPS

Passkeys are bound to the exact hostname and browsers only allow them over HTTPS. Put the app behind a reverse proxy that serves it over HTTPS (BunkerWeb, Traefik, Nginx Proxy Manager...) and enter that domain in the **Public domain** field at install time, then create your profile. To get the Admin dashboard (invite codes, AI Coach...), create your profile, copy its **Account ID** (Settings > Account) and put it in the **Admin user IDs** field of the app, then restart. See the [self-hosting guide](https://github.com/DuarteSantos8/openGym/blob/main/docs/SELF_HOSTING.md).

## Data

Everything is stored in `app-data/opengym/data/data`. Back it up.

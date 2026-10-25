# openGym

A self-hosted gym and body-weight tracker you actually own. No subscription, no ads, no telemetry.

## Features

- A routine per weekday over **5,600+ exercises** with animated demos
- Guided workouts: log every set, supersets and cardio included
- Body-weight tracking, stats, heatmap and personal records
- Installable on your phone (PWA), works offline and syncs between devices
- Passkey sign-in, optional admin dashboard and invite codes

## Important: passkeys need HTTPS

Passkeys are bound to the exact hostname and browsers only allow them over HTTPS. **Expose the app on a domain** (or use a local HTTPS domain) from the Runtipi app settings, then create your profile. The first profile created becomes admin only if `FIRST_USER_ADMIN=1` is set, see the [self-hosting guide](https://github.com/DuarteSantos8/openGym/blob/main/docs/SELF_HOSTING.md).

## Data

Everything is stored in `app-data/opengym/data/data`. Back it up.

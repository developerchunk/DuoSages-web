# DuoSages legal web

The public legal pages for the DuoSages app, served at https://legal.duosages.com.

| Path | Page |
|---|---|
| `/` | Index |
| `/terms` | Terms of Use |
| `/privacy` | Privacy Policy |
| `/delete-account` | Account deletion (the Google Play data-deletion URL) |
| `/about` | About the Sages |

Plain static HTML, no build step. Vercel deploys every push to `main`.

When a policy changes, update the "Last updated" date on that page, and keep the app's
in-app copy (`ui/components/AboutAndTerms.kt`) consistent with it.

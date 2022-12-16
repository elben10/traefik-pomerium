# Quickstart to reproduce error

1. Create an app registration in Azure AD - App Registration with the redirect uri https://pomerium.dev.localhost/oauth2/callback and generate a client secret
1. rename .env.example to .env and populate with tenant id, client id and client secret from the app registration
1. run `docker compose up`
1. access https://whoami.dev.localhost

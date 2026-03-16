# Forge Setapp

This project is a trial implementation of a Setapp app using Electron Forge.

Before building the app for distribution, make sure to set the following values in the configuration files:

- Set `<YOUR_APPLE_ID>`, `<YOUR_APPLE_ID_PASSWORD>`, and `<YOUR_TEAM_ID>` in `forge.config.ts` for notarization.
- Set `<YOUR_PUBLIC_KEY_CONTENT>` in `build/setappPublicKey.pem`

Build the app for distribution using the following command:

```sh
npm run package -- --arch=universal
```

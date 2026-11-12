# My_repository — Sileo source

This repository contains two rootless iOS jailbreak tweaks by **renlovecomputer**.

## Add to Sileo

`https://renlovecomputer.github.io/My_repository/`

## Compatibility

Both published tweaks have been tested **only on iOS 16.7.16**. Other iOS versions, devices and jailbreak environments are unverified.

## Packages

- GraviApps 1.0.0-8 (`com.demiany.graviapps`)
- GlyphTime 1.1.8 (`com.glyphtime.tweak`)

The package payloads are stored as Base64 text parts under `package-payload/`. The GitHub Actions workflow reconstructs the original `.deb` and PNG assets, regenerates the APT indices and publishes the `site/` directory to GitHub Pages.

## GitHub Pages setup

In the repository, open **Settings → Pages** and select **GitHub Actions** as the deployment source. The included workflow deploys automatically on pushes to `main`.

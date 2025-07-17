# Dumplin AI - TikTok OAuth Redirect

This GitHub Pages site handles TikTok OAuth redirects for the Dumplin AI mobile application.

## Purpose

This repository serves as a redirect endpoint for TikTok OAuth authentication in the Dumplin AI Flutter app.

## URL Structure

- **Main Page**: https://abrarshahok.github.io/dumplin/
- **OAuth Redirect**: https://abrarshahok.github.io/dumplin/auth/tiktok

## Setup

1. This repository is automatically deployed to GitHub Pages
2. The site is accessible at `https://abrarshahok.github.io/dumplin/`
3. TikTok OAuth redirects are handled at the `/auth/tiktok` path

## OAuth Flow

1. User initiates TikTok login in Dumplin AI app
2. TikTok redirects to `https://abrarshahok.github.io/dumplin/auth/tiktok`
3. This page receives the OAuth code/parameters
4. The Flutter app can then process the authentication

## Files

- `index.html` - Main page with OAuth handling
- `README.md` - This documentation file

## Configuration

In your TikTok Developer Console:

- Add `https://abrarshahok.github.io/dumplin/auth/tiktok` as a redirect URI

In your Flutter app:

- Set `TIKTOK_REDIRECT_URI=https://abrarshahok.github.io/dumplin/auth/tiktok`

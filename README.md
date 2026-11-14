# Somil Beats

Producer portfolio website for Somil Beats.

## Repository recovery status

This repository contains a partial recovery from the accessible Vercel deployment. The deployed file manifest was readable, but the Vercel file-content endpoint truncated many larger responses. Those files were not copied because a truncated file would be corrupt.

Recovered and verified:
- `src/package.json`
- `src/deployment/upload-client.js`

The original `README.md` was added as the initial repository commit.

## Project layout

The deployment manifest exposed a project rooted under `src/`, including API handlers, deployment helpers, public HTML, audio samples, image assets, scripts, CSS, JavaScript modules, and Vercel configuration. Most of those files remain unrecovered.

## Development

The recovered package manifest defines Node.js scripts for development, build, and tests. Their referenced scripts and test files were not present in the accessible deployment file listing, so the project cannot yet be built from this partial recovery.

## Security

Do not commit API keys, credentials, private environment files, or other secrets. Configure secrets as environment variables in the deployment platform.

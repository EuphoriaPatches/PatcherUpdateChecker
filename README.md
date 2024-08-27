# Euphoria Patcher - Version Update Repository

This repository is used solely for the Euphoria Patcher mod to check for the latest version updates. It is not intended for direct use by end-users.

## Purpose

The primary purpose of this repository is to serve as a backend for the Euphoria Patcher mod's update checker. The mod queries this repository to determine if a newer version is available.

## How It Works

- The mod fetches the latest release tag from this repository using the GitHub API.
- The version tag follows the format `X.Y.Z`
- If the fetched version is newer than the installed version, the mod will notify the user in the log and provide a link to download the update from Modrinth.

## Note

This repository is not intended for manual interaction or browsing by end-users.

# Claude Artifact Downloader

This is a user script that allows you to download artifacts from Claude conversations.

## Installation

1.  Install a user script manager like [Tampermonkey](https://www.tampermonkey.net/) or [Greasemonkey](https://www.greasespot.net/).
2.  Install the script from [here](https://github.com/anassk01/Claude-Artifact-Downloader/raw/main/script.user.js).

## Usage

Once installed, the script adds several commands to the Tampermonkey menu:

*   **Download All:** Downloads all artifacts in the current conversation.
*   **Download Range:** Prompts you to enter a start and end number to download a specific range of artifacts.
*   **Download Single:** Prompts you to enter the number of the artifact you want to download.
*   **List All:** Displays a list of all artifacts in the current conversation.

### How it Works

The script works by programmatically clicking the necessary buttons to open the artifact panel, select the desired artifact, and then trigger the download. It includes waits and checks to ensure the UI has loaded before proceeding.

# Download-API
# Video Download API

This API allows you to download videos from a specified URL by interacting with the `ssvid.net` website to fetch the highest available video quality up to 1080p.

## Features

- Accepts a video URL and interacts with `ssvid.net` to fetch download links.
- Returns the highest quality video download link up to 1080p.

## Requirements

- Node.js
- Puppeteer

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/video-download-api.git
    cd video-download-api
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Run the API locally:

    ```bash
    node index.js
    ```

4. Deploy the API (e.g., using Heroku or Vercel):

    - Follow the deployment instructions for your chosen platform.

## Usage

### Endpoint

- `POST /download`

### Request Body

- `url`: The URL of the video to download.

### Example

```bash
curl -X POST https://your-deployed-server/download -H "Content-Type: application/json" -d '{"url": "https://example.com/video"}'

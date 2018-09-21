# Puppeteer / Chromium Alpine Image
Based on `10-alpine` and `puppeteer@1.4.0`

## Usage
Puppeteer arguments to set:

```json
{
  "puppeteerExecutablePath": "/usr/local/bin/chromium",
  "puppeteerArgs": [
      "--disable-dev-shm-usage",
      "--no-sandbox",
      "--disable-setuid-sandbox"
  ]
}
```

# QR Links Repository

This repository manages dynamic redirect links for QR codes related to **SAM Logistics** and other projects.

## Purpose

- **Main Redirect:** Points to the main website (https://www.sam-logistics.de).
- **Product Redirects:** Specific QR codes for products like gloves, certificates, etc.

## Current Redirects

| Page           | URL                                       | Redirect Target                           |
|----------------|-------------------------------------------|-------------------------------------------|
| Main           | https://blancspace.github.io/qr-links/    | https://www.sam-logistics.de              |
| Gloves         | https://blancspace.github.io/qr-links/gloves | (to be added)                            |

## How to add a new redirect

1. Create a new `.html` file (e.g., `gloves.html`).
2. Use this template:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="refresh" content="0; url=YOUR_TARGET_URL">
    <title>Redirecting...</title>
  </head>
  <body>
    <p>If you are not redirected, <a href="YOUR_TARGET_URL">click here</a>.</p>
  </body>
</html>

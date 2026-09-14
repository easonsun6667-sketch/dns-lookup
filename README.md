# dns-lookup
A lightweight, browser-based DNS lookup tool for inspecting DNS records and related domain/network information.

## Features

- DNS record lookup
- DNSSEC information
- ECH (Encrypted Client Hello) information
- Domain and IP blacklist checks
- Mail/MX information
- RDAP lookup
- WHOIS fallback
- Certificate Transparency (CT) lookup
- Raw JSON response viewing
- Lookup history
- Watch/monitor functionality

## Data Sources

The application queries publicly available services and APIs, including:

- Cloudflare DNS
- RDAP services
- WHOIS API
- Cloudflare trace
- CertSpotter
- crt.sh
- ipwho.is

Availability and response formats of third-party services may change independently of this project.

## Usage

The project is designed as a static web application.

1. Download or clone the project.
2. Open `index.html` in a modern browser, or deploy the files to a static hosting service.
3. Enter a domain name or IP address.
4. Select the lookup function you want to use.

No server-side application is required for the basic static interface.

## Turnstile

If the project is configured to use Cloudflare Turnstile, replace the placeholder site key in `index.html` with your own Turnstile site key.

Do not publish private Turnstile secrets, API tokens, private keys, or other credentials in the repository.

## Deployment

Because the application is static, it can be deployed to services that support static HTML, CSS, and JavaScript hosting.

Examples include:

- GitHub Pages
- Cloudflare Pages
- Other static hosting platforms

Before deployment, review API endpoints, browser CORS requirements, rate limits, and any third-party service terms.

## Privacy

This repository should not contain:

- Personal domains
- Personal email addresses
- API keys or secrets
- Private tokens
- Private infrastructure addresses
- Personal analytics identifiers
- Deployment-specific credentials

Users should independently review browser-side API requests and third-party services before deploying a modified version.

## Project Structure

```text
.
├── index.html
└── README.md
```

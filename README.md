# dns-lookup

A lightweight, browser-based DNS lookup tool for inspecting DNS records and related domain and network information.

## Features

- DNS record lookup
- DNSSEC information
- ECH (Encrypted Client Hello) information
- Domain and IP blacklist checks
- Mail / MX information
- RDAP lookup
- WHOIS fallback
- Certificate Transparency (CT) lookup
- Raw JSON response viewing
- Lookup history
- Watch / monitor functionality

## How It Works

This project is designed as a static, client-side web application.

Lookup requests are made directly from the user's browser to the relevant public services. The project does not require a dedicated backend for its basic functionality and does not intentionally operate a central proxy or database for third-party lookup results.

Because requests are performed from the user's browser, availability, CORS policy, rate limits, authentication requirements, response formats, and other service-side policies may affect individual features.

## Responsible Use

This project is intended for legitimate network, DNS, domain, certificate, and security research purposes.

Users are responsible for how they use the software and for ensuring that their use complies with all applicable laws, regulations, contracts, acceptable-use policies, and terms of service.

In particular, users should not use the project to:

- Circumvent access controls or service restrictions
- Generate excessive or abusive traffic
- Perform bulk collection where it is not permitted
- Mirror, redistribute, or republish third-party data without appropriate permission
- Circumvent authentication, rate limits, quotas, or other technical controls
- Interfere with the operation or availability of external services
- Conduct unlawful reconnaissance, abuse, or other prohibited activity

The fact that a service can be queried from a web browser does not by itself grant permission for every possible use of that service.

If you deploy a modified or hosted version of this project, you are responsible for reviewing the current policies and usage requirements of the services your deployment contacts.

## Third-Party Services

This project may communicate with publicly accessible third-party services to obtain DNS, registration, network, certificate, and related information.

Third-party services are independent of this project. Their availability, APIs, response formats, rate limits, authentication requirements, pricing, acceptable-use policies, and terms may change without notice.

The project does not claim ownership of third-party services or third-party data returned by those services.

Where a third-party service imposes restrictions on production use, automated access, redistribution, commercial use, request volume, or other forms of usage, those restrictions remain the responsibility of the person operating the client or deployment.

## Project Structure


├── index.html
└── README.md


## Disclaimer

This software is provided for informational and educational purposes. It is provided on an "as is" basis without guarantees regarding availability, accuracy, completeness, or suitability for a particular purpose.

The project author is not responsible for how users operate the software, how external services respond to requests, or any consequences resulting from a user's use of the software.

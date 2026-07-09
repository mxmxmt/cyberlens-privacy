# CyberLens Privacy Policy

Effective date: July 9, 2026

## Overview

CyberLens is a browser extension for Chrome and Firefox that helps users investigate security artifacts such as IP addresses, domains, URLs, and file hashes by opening lookups in third-party security and OSINT services selected by the user.

CyberLens does not operate a backend service, require a user account, run analytics, show advertising, sell data, or track users.

## Information handled locally

CyberLens may handle the following information inside the user's browser:

- Text typed into the CyberLens popup.
- Text selected on a webpage.
- Link, media, or page URLs available through the browser context menu.
- The detected artifact type, such as IP address, URL, domain, or hash.
- The most recent artifact and category, stored locally in browser extension storage so the popup can restore the last workflow.

This information remains on the user's device unless the user chooses to open an external tool from CyberLens.

## Information CyberLens does not collect

CyberLens does not collect, store, or transmit:

- Names, email addresses, account identifiers, or contact details.
- Passwords, payment information, or authentication tokens.
- Browsing history for tracking or profiling.
- Cookies or cross-site tracking identifiers.
- Analytics, telemetry, advertising, or marketing data.

CyberLens does not sell, rent, or monetize user data.

## Third-party security tools

CyberLens provides shortcuts to third-party security and OSINT services. When the user clicks a tool button, uses a context menu action, or chooses to open all tools, CyberLens may open a third-party website and include the selected or entered artifact in that website's URL or search query.

Those requests are sent directly from the user's browser to the selected third-party service. CyberLens does not control those services, and their privacy practices are governed by their own policies.

Users should not submit sensitive, confidential, or private data to third-party tools unless they understand and accept the privacy policy of the selected service.

## Browser permissions

CyberLens requests browser permissions only to provide its extension features:

- `contextMenus`: to show CyberLens actions in the right-click menu.
- `activeTab` and `tabs`: to work with the current browser tab and open selected security tools.
- `storage`: to keep the most recent artifact locally in browser extension storage.
- Host access: to support content-script behavior such as recognizing selected artifacts on webpages.

These permissions are not used for advertising, analytics, tracking, or selling data.

## Data sharing

CyberLens does not automatically share user data with third parties. Data is sent to a third-party security tool only when the user chooses to open that tool from CyberLens.

## Retention and user control

The latest artifact may remain in local browser extension storage until it is overwritten, the browser clears extension data, or CyberLens is removed.

Users can avoid sending data to third-party services by not opening those tools from CyberLens. Users can also clear extension data through browser settings or remove the extension.

## Security

CyberLens does not operate a backend service and does not maintain a server-side database of user information. Interactions with third-party tools occur directly between the user's browser and the selected service.

## Changes to this policy

This privacy policy may be updated from time to time. Updates will be posted in this repository with a new effective date.

# nextcloud_server

## Description

Sick and tired of Google? This project documents my journey to self-host my own "Google Drive" using NextCloud. Frustrated with Google Drive's storage limits and the prospect of paying, I opted to spend $60 and invest time in setting up a self-hosted solution.

## Motivation

I reached my storage limit for Google Drive, prompting a $2/month payment demand for expanded storage. In response, I chose NextCloud for its features, especially in photo storage. Other considered options included OwnCloud and LibrePhotos.

## Installation and Setup

### 1. Hardware
Bought a computer from a surplus store.

### 2. Operating System
Installed Ubuntu Server on the computer.

### 3. Server Hardening
Followed documentation on hardening Ubuntu Server, noting changes for future installations.

### 4. NextCloud Installation
Installed NextCloud for self-hosted cloud storage.

### 5. Iterative Improvement
Repeated steps 1-3 with modifications, incorporating lessons from the initial attempt.

### 6. Security Assessment
Installed Greenbone Vulnerability Software on another computer and tested the server's security.

### 7. Configuration Tweaks
Discovered the need for further configuration adjustments and made necessary changes.

### 8. Final Setup
Reinstalled Ubuntu Server with the adjustments and ran another vulnerability assessment, achieving a much better score.

### 9. Domain Setup
Utilized DuckDNS to point a URL to my server's IP address and forwarded necessary ports.

### 10. Security Validation
Ran Greenbone assessment again after setting up the server, maintaining a good score.

### 11. Monitoring
Currently monitoring server activity and awaiting any potential security incidents.

## Links

- NextCloud: [https://github.com/nextcloud/all-in-one#how-to-use-this](https://github.com/nextcloud/all-in-one#how-to-use-this)
- DuckDNS: [http://www.duckdns.org/](http://www.duckdns.org/)
- Greenbone: [https://www.libellux.com/openvas/#enable-and-start-services](https://www.libellux.com/openvas/#enable-and-start-services)

## Results

The server is working well, allowing me to upload and access photos from anywhere with an internet connection. Although my internet provider flagged potential malicious activity, after thorough examination, the server appears secure.

Feel free to check out the [NextCloud documentation](https://github.com/nextcloud/all-in-one#how-to-use-this) for more information on using NextCloud.

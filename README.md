# nextcloud_server

## Description

My Process for avoiding paying $2 a month to google like the petty person I am.

## Motivation

I reached my storage limit for my google drive prompting them to ask me to pay $2 a month to expand my storage capabilities. I got mad and decided to instead spend $60 and a dozen hours figuring out how to self host my own "Google Drive." NextCloud seemed to be the option that most closely matched what I needed (primarily photo storage capabilities). Other options that didn't make the final cut were OwnCloud and LibrePhotos. Setting up NextCloud was easy enough. But learning how to harden a server and reduce the chances of being broken into was more difficult than I thought it would be. I'm not going to share the exact details of everything that I did, but here's a rough synopsis.

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

Formatted by ChatGPT

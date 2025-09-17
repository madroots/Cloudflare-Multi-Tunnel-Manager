# Cloudflare-Multi-Tunnel-Manager
Expose [multiple] local apps to the internet quickly

<img width="551" height="452" alt="image" src="https://github.com/user-attachments/assets/66d91c6a-e779-4b67-9f5e-ad141eb99117" />

A bash script to manage multiple local tunnels through Cloudflare’s `cloudflared`. Expose local development servers to the internet with a simple menu interface.

## Features

- No domain needed!
- Expose any port you want -> get https url = all in seconds
- Start, stop, and monitor multiple tunnels simultaneously
- Assign custom names to tunnels or just hit enter for random
- Stop individual tunnels or all at once
- No root required — runs as regular user

## Requirements

- `cloudflared` installed and in PATH
- `nc` (netcat) for local service detection (optional but recommended)

## Installation

1. Save the script
2. Make it executable: `chmod +x cf_tunnel_manager.sh`
3. run `./cf_tunnel_manager.sh`

Vibe coded in 5 seconds, works well tho.

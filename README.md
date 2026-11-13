# Brain Box showcase

A static, public-facing page about Brain Box (a Raspberry Pi guardian for a Docker stack).
One file, no build step, no external scripts, no tracking.

**Privacy rule:** this page contains no live data, addresses, hostnames, tokens or copied dashboard output.
Before every publish, run: `grep -n -i -E "192\.|10\.|:8765|webhook|sk-|0x[0-9a-f]{6}|\.local" index.html` (expect no output).

Preview locally: `python -m http.server 8080` then open http://localhost:8080

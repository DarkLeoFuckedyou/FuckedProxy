<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&height=8&color=00C8FF" width="100%"/>

# ⚡ TOOLS PROXY CHECKER

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=800&size=25&duration=2500&pause=800&color=00C8FF&center=true&vCenter=true&width=750&lines=PROXY+CHECKER;CONNECTION+ANALYSIS;DARK+LEO+@BangIadeshi" alt="Animated title"/>

**NEXT-GEN PROXY TESTING TOOL**

<img src="https://img.shields.io/badge/TOOL-PROXY%20CHECKER-00C8FF?style=for-the-badge&labelColor=050816"/>
<img src="https://img.shields.io/badge/INTERFACE-TERMINAL-00C8FF?style=for-the-badge&labelColor=050816"/>
<img src="https://img.shields.io/badge/DEVELOPER-%40BangIadeshi-00C8FF?style=for-the-badge&labelColor=050816"/>

<br/>

[ FEATURES ](#-features) •
[ INSTALLATION ](#-installation) •
[ USAGE ](#-usage) •
[ DEVELOPER ](#-developer)

</div>

---

## ◈ OVERVIEW

**TOOLS PROXY CHECKER** is a Python terminal utility for checking proxy connectivity and reviewing test results through a clean, command-line interface.
Designed for users who want a straightforward workflow for proxy testing on Python-compatible systems, including Termux.

## ◈ FEATURES

- **HTTP / HTTPS** — Test supported HTTP proxy connections.
- **SOCKS4 / SOCKS5** — Test supported SOCKS proxy connections.
- **Connection Latency** — Measure response time during testing.
- **Exit IP Verification** — Check the public IP observed through a proxy.
- **Test Summary** — Review working and failed proxy counts.
- **Result Export** — Save working proxies when supported by the script.
- **Terminal Interface** — Colorful, readable status messages.
- **Termux Compatibility** — Run in a compatible Android Python environment.

*Available features depend on the implementation in the Python script.*

## ◈ REQUIREMENTS

- Python 3
- `requests`
- `termcolor`
- `cfonts`
- `PySocks` — required for SOCKS proxy support in Requests.

## ◈ INSTALLATION

### 01 — Clone the repository

```bash
git clone https://github.com/alexhuntercctteam/FileSecurity.git
```

### 02 — Enter the project directory

```bash
cd FileSecurity
```

### 03 — Install dependencies

```bash
python -m pip install requests termcolor cfonts PySocks
```

### 04 — Run the proxy checker

```bash
python proxy_checker.py
```

Run the command using the actual Python filename in your proxy checker project.

## ◈ USAGE

1. Launch the Python script.
2. Enter a proxy in `IP:PORT` format.
3. Run the available connection test.
4. Review the connection status and response time.
5. Check the summary and exported results, if available.

### Proxy format

```text
IP:PORT
```

Example format:

```text
127.0.0.1:8080
192.0.2.10:1080
```

These addresses illustrate the format only; they are not verified working proxies.

## ◈ RESULT PREVIEW

```text
TOOLS PROXY CHECKER

Total Tested : 10
Working      : 6
Failed       : 4

Saved To     : working_proxies.txt
```

*Illustrative output only. Actual results depend on the script and tested proxies.*

## ◈ SECURITY

- Test proxies you own or are authorized to use.
- Avoid sending passwords, tokens, or sensitive data through untrusted proxies.
- Public proxies can be unreliable or malicious.
- A successful connection does not guarantee anonymity or privacy.

## ◈ DEVELOPER

<div align="center">

<img src="https://img.shields.io/badge/NAME-DARK%20LEO-00C8FF?style=for-the-badge&labelColor=050816"/>

<img src="https://img.shields.io/badge/DEVELOPER-%40BangIadeshi-00C8FF?style=for-the-badge&labelColor=050816"/>

<a href="https://t.me/BangIadeshi">
<img src="https://img.shields.io/badge/TELEGRAM-CONTACT-00C8FF?style=for-the-badge&logo=telegram&logoColor=white&labelColor=050816" alt="Telegram contact"/>
</a>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=00C8FF" width="100%"/>

### `DARK LEO` — TOOLS PROXY CHECKER

**TEST SMART. ANALYZE CONNECTIONS. STAY SECURE.**

<sub>Developed by @BangIadeshi</sub>

</div>

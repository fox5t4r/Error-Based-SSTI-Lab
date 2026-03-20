# Error-Based SSTI Lab

Top 10 web hacking techniques of 2025 에 소개되었던 Successful Errors: New Code Injection and SSTI Techniques의 주제에 대하여 실습해볼 수 있는 Lab 입니다.

A CTF challenge designed to teach **Error-Based Server-Side Template Injection (SSTI)** in Jinja2/Flask.

## Overview

This is a "Template Preview" web application that lets users input Jinja2 template code and renders it on the server. However, the rendered output is **never shown** — only a fixed success message or raw error messages are returned.

The challenge is to extract the flag using **error-based exfiltration** techniques.

## Quick Start

```bash
docker compose up --build
```

Access at `http://localhost:52411`

## Challenge Details

| Item | Detail |
|------|--------|
| Category | Web Exploitation |
| Technique | Error-Based SSTI |
| Framework | Flask / Jinja2 |
| Difficulty | Easy |
| Filtering | None |

## Setup

### Requirements

- Docker
- Docker Compose

### Environment Variables

| Variable | Default | Description |
|----------|---------|-------------|
| `FLAG` | `WSL{fake_flag}` | The flag to capture |

## License

For educational purposes only.

# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please **do not** open a public issue.

Instead, report it privately by:
- Opening a [GitHub Security Advisory](https://docs.github.com/en/code-security/security-advisories) on this repository, or
- Contacting the project owner directly via the contact info on their GitHub profile.

Please include:
- A description of the vulnerability
- Steps to reproduce it
- Any potential impact you've identified

I'll do my best to respond promptly and address valid reports as quickly as possible.

## Sensitive Configuration

This project connects to external services (Base44, Meta, TikTok, OpenAI). Credentials and tokens should **never** be committed to the repository.

Always store sensitive values in a `.env.local` file (which is listed in `.gitignore`):

```env
VITE_BASE44_APP_ID=...
VITE_BASE44_APP_BASE_URL=...
```

Never hardcode API keys, tokens, or secrets directly in source files.

## Scope

This is a personal project. While I take security seriously:
- There are no guaranteed SLAs for response times.
- Not all reported issues may be acted upon immediately.

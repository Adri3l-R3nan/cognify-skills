# Security Policy

## Reporting a Vulnerability

If you discover a security issue in any Cognify skill, please report it responsibly by [opening a private security advisory](https://github.com/Yarmoluk/cognify-skills/security/advisories/new) rather than opening a public issue.

## Scope

These skills are instruction files (markdown) executed by AI agents. They do not execute arbitrary code, make network requests, or access filesystems directly. Security considerations are limited to:

- Prompt injection vectors in skill instructions
- Data exposure through overly broad tool permissions
- Unintended information disclosure in skill outputs

## Supported Versions

| Version | Supported |
|---------|-----------|
| 1.0.x   | Yes       |

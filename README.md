# Jarvis Security Analyzer

An AI-powered security log analysis and detection engineering tool built using Python and Qwen Coder.

## Features

- Secure API authentication using getpass
- Structured JSON security classifications
- Concurrent batch log processing
- Automated severity scoring
- CSV and JSON result exports
- AI-generated Sigma detection rules
- Prompt injection defenses
- Offline unit testing

## Security Analysis Results

The tool successfully analyzed 200 SSH authentication log entries.

| Classification | Count |
|---|---:|
| Benign | 119 |
| Suspicious | 73 |
| Malicious | 8 |
| Total | 200 |

## Technologies

- Python
- Qwen Coder
- Jupyter Notebook
- OpenAI-compatible API
- Sigma
- JSON and CSV

## Security

API keys are entered securely at runtime and are not stored in source code. Untrusted log entries are processed using hardened prompts to mitigate prompt injection risks.

## Project Purpose

Developed for IS2083 Advanced Scripting at the University of Texas at San Antonio to demonstrate AI-assisted security automation, log analysis, and detection engineering.

This project is intended for educational purposes.

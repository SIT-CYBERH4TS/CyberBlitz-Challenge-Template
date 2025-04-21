# Web Me
How hard can webbing get

## Summary
- **Author:** `Shank`
- **Telegram Username:** `@CyberH4TS`
- **Category:** `Web`
- **Difficulty:** `Easy`

## Hints
- `It's a web service`

## Files
- [`challenge.txt`](./dist/challenge.txt)

## Services
- [`TestService`](./service/TestService) (port 8000)

## Setup Guide
1. Build Docker image and container from docker-compose.yml
```
docker-compose up --build -d
```
2. To test whether it's working, visit: `http://127.0.0.1:8000` --> You should see a website.
3. Update `challenge.yml` to inform participants the IP and port 8000 to access the challenge.

## Direct Solution
Direct Solution to this challenge
1. On terminal, execute `curl 127.0.0.1:8000`

## Flag
- `CyberBlitz2025{flag}`

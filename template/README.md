# [Challenge Name]
[Challenge Description]

## Summary
- **Author:** `[Name]`
- **Telegram Username:** `[Telegram Username]`
- **Category:** `[Category]`
- **Difficulty:** `[Difficulty]`

## Hints (Optional)
- `[Hint Content]`

## Files
- [`<filepath to dist>`](./dist/challenge.txt)

## Services (Optional)
- [`<Service path folder name>`](./service/TestService) (port 8000)

## Setup Guide (Optional)
1. Build Docker image and container from docker-compose.yml
```
docker-compose up --build -d
```
2. To test whether it's working, execute: `nc 127.0.0.1 8000` --> You should get a connection.
3. Update `challenge.yml` to inform participants the IP and port 8000 to access the challenge.

## Direct Solution
Direct Solution to this challenge
1. < Step 1, for example: After connection, enter `LFILE=file_to_read` >
2. < Step 2, for example: For the 2nd part, enter `sudo 7z a -ttar -an -so $LFILE | 7z e -ttar -si -so` >
3. < Step 3, for example: Last part, enter `cat flag.txt` >

## Flag
- `CyberBlitz2025{example}`

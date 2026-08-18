# Day 2 — HTTP & DevTools

## SauceDemo
- 503 → Backtrace error-reporting request.
- Not the actual login request.
- Login is handled client-side.

## The Internet Login

**Correct:** POST → 303 → GET /secure → 200  
**Wrong:** POST → 303 → GET /login → 200

- Location header showed success/failure.
- Set-Cookie: Yes for both.

## Key Lesson
Status code alone isn't enough. Check **request, status, headers, Location, cookies, and final page**.

# Secure Coding

## Coding Style
- Repository Pattern

## Vulnerabilities
- CORS
- CSRF
- Web Socket (Planned)
- JWT attack (jwt placed in req header, used for authentication-authorization, can be manipulated)

## Database

- User
- Post
- PostImage -> File-Upload-to-RCE
- Like -> Like Manipulation
- Comment (Reply) -> XSS
- Tag -> XSS
- Mention -> XSS
- BookMark -> IDOR
- Follow -> Follow Manipulation
- Notification -> Path Traversal
- OTP -> Response Manipulation, No Time constraints, no rate limit, invalid -> valid, no backend check from frontend.
- Report -> XSS, SQLI, HTML Injection, XXE, Command Injection,

### Planned
- Views

## Tenant Users level
- Admin
- Moderator
- End User

## Post Visibility
- Only Me
- Follower Only
- Public

## Features
- Run own mail-server with docker
- Fixed pre-registered 10 users
- Send mail
- Share post

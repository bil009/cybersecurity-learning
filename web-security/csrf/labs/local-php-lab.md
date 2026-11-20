# Local PHP CSRF Lab

- Environment: Local PHP lab
- Topic: Cross-Site Request Forgery
- Status: Practiced

## Objective
Understand how a browser can submit authenticated requests and how applications can protect state-changing actions.

## Concepts explored
- Session-based authentication
- Browser cookies
- Authenticated requests
- CSRF tokens
- Request modification
- HTTP methods
- CSRF protection

## Work completed
- Built a local PHP CSRF demonstration.
- Tested authenticated request behavior.
- Investigated token validation.
- Modified requests.
- Explored CSRF scenarios and mitigation.

## Further revision
- Explain the difference between authentication and CSRF protection.
- Identify which request properties are validated.
- Compare missing and invalid tokens.
- Verify the server-side protection.
- Explain SameSite behavior.

## Remediation
- Implement and validate CSRF tokens.
- Configure SameSite appropriately.
- Avoid state-changing GET requests.
- Use additional origin validation where appropriate.

## Lessons learned
A browser's automatic handling of authentication cookies does not establish that a request was intentionally initiated by the authenticated user.

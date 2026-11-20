# Broken Access Control

## Learning status
Study initiated.

## Core concepts
- Authentication vs authorization
- Horizontal privilege escalation
- Vertical privilege escalation
- Insecure Direct Object References (IDOR)
- Forced browsing
- Access control at the server
- Method-based authorization
- Role-based access control

## Testing methodology
1. Identify roles and permissions.
2. Map endpoints and resources.
3. Capture requests.
4. Compare access between accounts and roles.
5. Test object identifiers and permitted actions.
6. Verify unauthorized access or actions.
7. Review remediation.

## Remediation
- Enforce authorization server-side on every request.
- Deny by default.
- Validate permissions for the specific object and action.
- Avoid relying on hidden buttons or client-side restrictions.
- Test access control systematically.

## Practice
- OWASP Top 10 A01
- PortSwigger Access Control labs

## Status
Learning and lab practice pending.

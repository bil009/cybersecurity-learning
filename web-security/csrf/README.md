# Cross-Site Request Forgery (CSRF)

## Topics explored
- Authentication and browser cookies
- Authenticated requests
- CSRF tokens
- Missing and invalid tokens
- HTTP methods
- Method-dependent behavior
- SameSite cookies
- Burp Suite request modification

## Practice
- Built a local PHP CSRF demonstration.
- Explored PortSwigger CSRF labs.
- Tested request behavior and token validation.
- Investigated method changes and request handling.

## Testing methodology
1. Identify a state-changing action.
2. Understand how the request is authenticated.
3. Inspect token validation and request requirements.
4. Test in an authorized lab.
5. Verify whether the action succeeds.
6. Review the protections.

## Remediation
- Proper CSRF token validation
- Appropriate SameSite cookie configuration
- Origin / Referer verification where appropriate
- Avoid state-changing GET requests
- Additional protections appropriate to the application

## Status
Practiced; continued revision ongoing.

# OS Command Injection

## Learning status
Exploratory.

## Current exploration
- Web applications invoking operating-system commands
- Linux shell behavior
- Challenge source-code inspection
- HTTP requests with curl
- GET and POST request construction
- URL encoding
- Input and execution contexts

## Analysis methodology
1. Identify the application feature.
2. Inspect the source where available.
3. Trace input to command execution.
4. Understand the command construction.
5. Test in an authorized lab.
6. Verify behavior.
7. Analyze the root cause and remediation.

## Remediation
- Avoid shell execution where possible.
- Prefer APIs and libraries over shell commands.
- Avoid constructing commands from untrusted input.
- Use safe argument handling.
- Apply least privilege.

## Practice
- pwn.college

## Status
Exploratory; fundamentals require continued practice.

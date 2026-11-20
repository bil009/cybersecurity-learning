# Cross-Site Scripting (XSS)

## Topics explored
- Reflected XSS
- Stored XSS
- DOM-based XSS
- HTML and JavaScript contexts
- Sources and sinks
- DOM manipulation
- Filter and validation behavior

## Practice
- Completed all six XSS Game DOM XSS levels.
- Intermediate / advanced source-to-sink assessment: 3/8.

## Analysis methodology
1. Identify input sources.
2. Trace the input through the application.
3. Identify the sink.
4. Determine the execution context.
5. Understand encoding, sanitization and validation.
6. Test in an authorized environment.
7. Verify execution and impact.

## Remediation
- Context-aware output encoding
- Safe DOM APIs
- Avoid unsafe HTML sinks
- Appropriate sanitization when HTML is required
- Content Security Policy as an additional layer

## Status
Practiced; source-to-sink reasoning requires revision.

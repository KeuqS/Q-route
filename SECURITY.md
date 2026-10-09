# Security Policy

## Project status

Q Route is an early-stage independent open-source project. It is not a production emergency service.

The project may contain experimental code that has not been independently audited or approved for real-world safety use.

## Supported versions

| Version | Supported |
| --- | --- |
| Development branch | Yes, for security reports |
| Released versions | Not available yet |

## Reporting a vulnerability

Please do not report security vulnerabilities through a public issue.

Report vulnerabilities privately through GitHub's private security advisory feature when it is available for this repository.

If private reporting is not available, contact the repository maintainer privately through their GitHub profile.

Include:

- A description of the vulnerability.
- The affected file, component, or version.
- Steps to reproduce the issue.
- Possible impact.
- A suggested fix, if available.
- Any proof-of-concept code required to understand the issue.

Do not include real passenger data, live locations, personal phone numbers, API keys, or emergency-service credentials in a report.

## Sensitive data

Never commit the following to the repository:

- API keys.
- Passwords or tokens.
- Private certificates.
- Personal phone numbers.
- Real passenger or driver information.
- Live or historical personal location data.
- Emergency-service credentials.
- Unredacted production logs.

## Responsible disclosure

Please allow the maintainers reasonable time to understand and address a vulnerability before publicly disclosing technical details.

The project may acknowledge security contributors after a fix, unless they prefer to remain anonymous.

## Security limitations

Q Route is not currently suitable for real emergency use. Contributions must not imply that the system guarantees rescue, police response, or uninterrupted location tracking.

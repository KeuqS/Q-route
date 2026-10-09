# Privacy Principles

## Purpose

Q Route explores a safety workflow for ride-hailing and campus transportation.

This document describes the privacy principles that should guide any implementation of the project.

## Data minimisation

Implementations should collect only the data required for an active ride and its safety workflow.

Potential data may include:

- Pickup and destination information.
- Route information.
- Approximate or precise ride location.
- Ride timestamps.
- Safety-event status.
- Passenger confirmation status.
- Trusted-contact notification status.

Implementations should avoid collecting unrelated personal information.

## Consent

Location monitoring must require clear user consent.

Users should understand:

- When monitoring begins.
- What information is collected.
- Why it is collected.
- Who may receive it.
- When monitoring ends.
- How long information may be retained.

Consent should not be hidden inside unrelated terms or confusing interface design.

## Active-ride limitation

Location tracking should be limited to the active ride and the minimum period required to process a safety event.

The system should not continuously track a person before or after an active ride without a separate, clear legal and technical basis.

## Access control

Only authorized components and people should access ride-safety information.

Implementations should use:

- Authentication.
- Role-based access control.
- Encrypted network communication.
- Secure storage.
- Access logs.
- Short-lived sharing links where applicable.

## Data retention

Implementations should define a clear retention period.

Location and incident data should not be retained indefinitely. Data that is no longer required should be securely deleted or anonymised.

The exact retention period may depend on the deployment, applicable law, and incident-review requirements.

## Sharing

Location and ride information should not be shared publicly.

Sharing with a trusted contact or emergency service should happen only through an explicit safety workflow and only with the minimum information required.

## Development and testing

The project should use:

- Simulated locations.
- Synthetic user accounts.
- Test phone numbers.
- Redacted logs.
- Non-production credentials.

Real passenger or driver data must not be used in development or testing without appropriate authorization and protection.

## User rights

A real deployment should provide appropriate mechanisms for users to understand, access, correct, delete, or withdraw consent for their information, subject to applicable law and legitimate safety or legal requirements.

## Disclaimer

This document describes project principles, not a legal privacy notice or a complete compliance guarantee.

Any production deployment must obtain appropriate legal, privacy, security, and operational review before handling real user data.

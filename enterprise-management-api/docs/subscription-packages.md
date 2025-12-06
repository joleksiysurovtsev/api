# Subscription Packages

Endpoints focusing on subscription packages and SIM specifications include:

- `GET/POST /enterprises/{enterprise_id}/subscription-packages` for managing enterprise subscription packages.
- `GET /enterprises/sim-specifications` to list available SIM specifications.
- `POST /enterprises/subscription_packages/{subscription_package_id}/deactivate` to deactivate a package.

Schemas for these resources live in `schemas/SubscriptionPackage.yaml`, while shared enums come from `schemas/common.yaml`.

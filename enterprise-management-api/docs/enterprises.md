# Enterprises

This section of the Enterprise Management API covers enterprise lifecycle operations:

- `GET /enterprises` to list accessible enterprises.
- `POST /enterprises` to create a new enterprise.
- `GET /enterprises/{enterprise_id}` to read enterprise details.
- `PUT /enterprises/{enterprise_id}` to update enterprise data.
- `POST /enterprises/{enterprise_id}/statuses` to change an enterprise status.

These operations rely on shared request parameters from `parameters/common.yaml` and enterprise schemas defined in
`schemas/Enterprise.yaml`.

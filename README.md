# Orders Reconciliation Fixture

This repository contains a compact dbt project for exploring an order-reconciliation transformation.

## Project files

- `models/sources.yml` declares the input relation and model metadata.
- `models/unresolved_order_summary.sql` contains the transformation query.
- `dbt_project.yml` configures the project and model defaults.
- `profiles.yml` contains local settings whose credentials come from environment variables.

The project can be inspected without running dbt or connecting to a database. Runtime credentials are not included in this repository.

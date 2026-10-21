# Software-Architecture
Repository to handle Structurizr DSL diagrams

## Structurizr entry point

Use `C4Diagram.txt` as the single Structurizr DSL entry point. It contains the
system context, one logical container view, backend component, ETL component,
dynamic enrolment flow, code, and production deployment views.

The container view is the canonical logical application model: the SPA,
Backend API, ETL pipeline, availability cache and enrolment queue, operational
database, report and data-export storage, and its external integrations. AWS
delivery, operations, and infrastructure details are represented separately in
the production deployment view.

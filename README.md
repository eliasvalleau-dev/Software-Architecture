# Software-Architecture
Repository to handle Structurizr DSL diagrams

## Structurizr entry point

Use `C4Diagram.txt` as the single Structurizr DSL entry point. It contains the
system context, one logical container view, backend component, ETL component,
dynamic enrolment flow, and production deployment views.

The container view is the canonical logical application model: the SPA,
Backend API, ETL pipeline, availability cache and enrolment queue, operational
database, report and data-export storage, and its external integrations. AWS
delivery, operations, and infrastructure details are represented separately in
the production deployment view.

The stakeholder-facing views include Students, Faculty Members, Academic
Administrators, and System Administrators.

## Relationship scoping

Each view explicitly includes only the elements at its C4 abstraction level.
The Context view uses system-to-system and actor-to-system relationships; the
Container view uses actor-to-SPA and container-to-container relationships; and
the component, ETL, dynamic, and deployment views use their respective
relationships. This prevents parent and child relationships from being rendered
as incomplete edges in higher-level diagrams.

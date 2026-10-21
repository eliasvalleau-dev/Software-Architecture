# Software-Architecture
Repository to handle Structurizr DSL diagrams

## Structurizr entry point

Use `C4Diagram.txt` as the single Structurizr DSL entry point.

During the staged consolidation of the former cloud/deployment and code
workspaces, their unmigrated source is retained as commented migration
sections at the end of `C4Diagram.txt`. Each section is removed as its
corresponding live view is integrated. The comments are intentionally ignored
by Structurizr.

The current live views are the system context, logical container, backend
component, ETL component, dynamic enrolment flow, and production deployment
views. The code view remains in its commented migration source until its
dedicated consolidation commit.

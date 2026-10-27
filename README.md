# Software-Architecture
Repository to handle Structurizr DSL diagrams

## Structurizr DSL files

The diagrams are maintained as separate Structurizr workspaces:

- `C4Diagram.txt` contains the system context, logical container, backend
  component, ETL component, and dynamic enrolment views. It includes the
  Academic Administrator stakeholder and retains the latest constrained
  Container and backend Component Views.
- `CorrectedCloudArchitecture.txt` contains the focused AWS production
  deployment overview and Availability Zone B drill-down.

Import or render each file independently. Do not merge these workspaces into a
single DSL file: their models deliberately use separate element definitions and
view scopes.

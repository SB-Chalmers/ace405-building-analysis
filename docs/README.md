# Workflow and limitations

The supplied definition supports the master's course ACE405, *Design and performance optimization in architecture*. Its documented scope is building model creation, BPS/LCA simulation and output processing.

## Documented modules

- Modelling: define program and construction, assemble a Honeybee model and obtain climate data.
- Analysis: weather visualization, model property visualization, simple and detailed energy simulations, daylight, glare and LCA.

The [original README](original-readme.md) is preserved unchanged. Its screenshot is available at [../img/screenshot.png](../img/screenshot.png); this link accounts for the README's relocation.

## Environment and scientific scope

The original instructions specify Rhino 7 and Ladybug Tools 1.6.0 with OpenStudio and Radiance. They do not record the exact operating system, Rhino service release, OpenStudio/Radiance versions, analysis settings or expected numerical results. Compatibility with newer plugin versions has not been established by this migration.

The binary Grasshopper definition and its scientific methods were preserved unchanged. No simulation or model validation was performed as part of the documentation work. Use [reproduce.md](reproduce.md) to record a verified run before treating the workflow as reproduced.

## Project-member TODOs

- Supply or identify a small building example, its geometry assumptions and any external references held by the definition.
- Record the EPW source/version and data terms, material/LCA datasets, units, system boundaries and analysis settings actually used.
- Record a verified software environment, run procedure and expected outputs.
- Confirm the complete citation author list, funding, project status and any thesis, paper or software/data archive identifiers. No DOI is currently supplied in this repository.

See [data provenance](../data/README.md) and [migration provenance](migration.md).

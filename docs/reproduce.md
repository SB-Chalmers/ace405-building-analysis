# Run the supplied Grasshopper workflow

These instructions summarize the original graphical entry point. A complete independent reproduction remains pending the input and environment details below.

## Environment

- Rhino 7 with Grasshopper.
- Ladybug Tools 1.6.0, with its full OpenStudio and Radiance installation.
- TODO: record operating system, Rhino service release and exact bundled engine versions from a successful run.

## Inputs

No separate Rhino example model, EPW file or LCA database is included in this extracted folder. The contents of any data internalized in the binary definition have not been inspected during migration. Obtain the project inputs and record their provenance in [the data inventory](../data/README.md).

## Graphical steps

1. Start Rhino 7 and open Grasshopper.
2. Open [`230904ace405_analysis_script.gh`](../230904ace405_analysis_script.gh).
3. Follow the instructions embedded in the definition to define program and construction, assemble the Honeybee model and obtain climate data. Resolve any referenced files using the intended project inputs.
4. Run the relevant energy, daylight, glare or LCA analysis modules using the settings supplied in the definition.
5. Inspect the definition's visualization and result components. Record selected inputs, units, analysis settings and output locations with the run.

TODO: add exact component settings and a minimal worked example after a project member has run the preserved definition. The source README does not provide these details.

## Expected outputs and checks

The original documentation describes model/property and weather visualization, energy simulation, daylight, glare and LCA outputs. It provides an [overview screenshot](../img/screenshot.png), but no numerical reference results, output schema or acceptance tolerances.

Check that the intended model, weather period and material inputs are used before comparing results. TODO: add reference outputs and checks for a known example. No automated tests or Rhino/Grasshopper execution were performed during migration.

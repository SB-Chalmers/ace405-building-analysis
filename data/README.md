# Input data and provenance

| Material | Role and availability | Provenance and outstanding information |
| --- | --- | --- |
| `230904ace405_analysis_script.gh` | Preserved workflow; any internalized data are unverified | Extracted unchanged from the source folder at the commit recorded in [migration.json](../migration.json). |
| `img/screenshot.png` | Documentation image | Preserved source screenshot; not a numerical reference dataset. |
| Building geometry/model | Required analysis input; no separate example model supplied | TODO: supply a small example, model assumptions, units and any linked files. |
| EPW weather | Required climate input; no separate EPW supplied | TODO: record station/location, provider, version, retrieval route and data terms used in a verified run. |
| Construction and LCA data | Inputs used by the chosen modules; provenance unrecorded in the source README | TODO: identify datasets, versions, units, system boundaries and access/license terms. |

The [migration manifest](../migration.json) contains original paths, pinned source URLs and SHA-256 checksums. No separate archived dataset or Zenodo DOI was supplied. Do not infer the origin or license of external data from the code's MIT license; record the terms for each dataset when it is added or referenced.

See [reproduction instructions](../docs/reproduce.md) for the graphical workflow. Keep generated simulation outputs outside Git unless a small reference result is needed for a documented check.

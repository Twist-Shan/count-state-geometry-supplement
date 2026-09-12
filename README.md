# Interactive geometry supplement

Download `index.html` and open it in a browser.

```text
COUNT-STATE GEOMETRY — ANONYMOUS INTERACTIVE SUPPLEMENT

Open index.html in a modern browser. No installation, server, login, or network is required.
Qwen3-8B, all paper-numbered layers L1–L36, non-thinking and CoT-reasoning.
The paper preset selects L13/L31 and displays the 100 secondary-confirmation states per mode.
Each prompt has gold N=10. Colors denote occurrence / running index k=1,...,10.
Non-thinking: evidence span-end state. CoT: item-end state in a strict indexed numeric trace.
The restricted cohort contains 30 paired complete trajectories: 20 discovery and 10 confirmation.
These are secondary splits: all 11 source-discovery seeds are retained; of the 19 source-confirmation seeds,
10 are hash-selected as secondary confirmation and the remaining 9 are added to discovery.
This is a selected complete-trace cohort, not the full population of model outputs.
Trace-format selection and the secondary split followed exploration; this is not a fresh confirmation cohort.
Viewer labels are one-based. Exported JSON layer keys remain zero-based; CSV includes both conventions.
Display layers independently maximize discovery grouped-OOF NCC balanced accuracy; ties use
discovery logistic balanced accuracy, then the earlier layer. Confirmation was not used for layer selection.
The source report's default non-thinking layer (L15) uses a different selection score; the paper preset is L13.
PCA is fitted separately on discovery states for every layer and mode. The displayed three components
are for visualization; saved confirmation NCC is a 16-component readout (chance 10%), not a 3D re-fit.
Centroids and their connecting polyline describe the displayed subset. They are not fitted classifier centers
and the line does not represent a single observed trajectory. Filtering never recomputes the saved NCC.
PCA signs and bases can differ across layers/modes. Shared camera does not imply a shared coordinate basis.
Clouds are centered and uniformly fitted separately to each viewport; sizes across panels/layers are not
comparable magnitudes. The paper view additionally applies the paper's 0.75 left-panel display factor.
Axis triads are orientation cues. Hover and CSV preserve original PCA coordinate values.
Arrow keys rotate focused plots, +/- zoom, 0 resets the camera. Mouse drag rotates; wheel zooms.
Sample IDs are anonymous, paired, and consistent across all layers and modes.
layer_metrics.csv contains all 72 saved layer/mode metric records. Coordinates can be exported in the viewer.

```

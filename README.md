# Raw AM-AFM amplitude and phase curves of anti-IgM layers on Au

Raw amplitude–phase–distance curves acquired by amplitude-modulation AFM (NT-MDT NTEGRA Spectra, semi-contact mode, Bruker RTESPA-300 cantilevers) on two Au/anti-IgM samples:

- **Film:** continuous anti-IgM film (0.1 mg/mL), 64 curves
- **Clusters:** isolated anti-IgM clusters, 68 curves

Associated manuscript: *Aggregation-Dependent Nanomechanics of Quasi-Two-Dimensional Antibody Films at Bio–Inorganic Interfaces Probed by Amplitude Modulation AFM in ambient conditions* (A. Khaliq, C. Di Franco, E. Macchia, L. Torsi, G. Scamarcio).

## Contents

| File | Content |
|---|---|
| `Film raw data Amplitude & Phase.zip` | 64 amplitude/phase curve pairs of the film (128 Excel files) |
| `Cluster raw data Amplitude & Phase.zip` | 68 amplitude/phase curve pairs of the clusters (136 Excel files) |

## File format

Each curve is stored as two Excel files with the same numerical identifier:
`Amplitude<id>.xlsx` (amplitude signal) and `phase<id>.xlsx` (phase). Each file has two columns:

| column | content |
|---|---|
| `X` | z-piezo displacement (as exported by the instrument software) |
| `Y` | raw amplitude signal (nA) in `Amplitude<id>`, or raw phase (degrees) in `phase<id>` |

The amplitude is converted to nm with the amplitude sensitivity, and a constant offset is applied to the phase so that the free-oscillation region is at −90°, as described in Section S3 of the Supporting Information of the manuscript.


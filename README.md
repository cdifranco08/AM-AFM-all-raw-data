Raw amplitude–phase–distance curves acquired by amplitude-modulation AFM (NT-MDT NTEGRA Spectra, semi-contact mode, Bruker RTESPA-300 cantilevers) on two Au/anti-IgM samples:

data/film/ – continuous anti-IgM film (0.1 mg/mL), 64 curves data/clusters/ – isolated anti-IgM clusters, 68 curves

Associated manuscript: Aggregation-Dependent Nanomechanics of Quasi-Two-Dimensional Antibody Films at Bio–Inorganic Interfaces Probed by Amplitude Modulation AFM in ambient conditions (A. Khaliq, C. Di Franco, E. Macchia, L. Torsi, G. Scamarcio). File format

One CSV file per curve, named _<curve_id>.csv, with columns:

column content z_um z-piezo displacement (µm, as exported by the instrument software) amplitude_nA raw amplitude signal (nA); conversion to nm with the amplitude sensitivity, see SI Section S3 phase_deg raw phase (degrees), including the instrumental offset (set to −90° in free oscillation during processing, SI Section S3)

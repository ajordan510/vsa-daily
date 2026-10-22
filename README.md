# VS&A Daily

A growing collection of short articles on vibration, shock, acoustics, and structural dynamics, prepared for Alex Jordan. Each PDF includes its references, figures, and worked examples. The repository also includes hands-on training assignments.

## Reading index

26 articles · September 30–October 22, 2026

| Date | Article | Edition | Pages |
| --- | --- | --- | ---: |
| 2026-10-22 | [The peak that grows while gRMS stays still](articles/2026/10/2026-10-22_VSA_Lesson_Peak_Factor_Duration.pdf) | Daily | 6 |
| 2026-10-21 | [Predicting component shock after a design change](articles/2026/10/2026-10-21_VSA_Special_FEM_Shock_Response.pdf) | Special | 8 |
| 2026-10-21 | [The stiffness hiding above your modal cutoff](articles/2026/10/2026-10-21_VSA_Lesson_Residual_Flexibility.pdf) | Daily | 6 |
| 2026-10-20 | [Same SPL, different panel loads](articles/2026/10/2026-10-20_VSA_Lesson_Same_SPL_Different_Panel_Loads.pdf) | Daily | 6 |
| 2026-10-19 | [The damping your window added](articles/2026/10/2026-10-19_VSA_Lesson_Exponential_Window_Damping.pdf) | Daily | 6 |
| 2026-10-18 | [X-56A: stable flight does not prove passive stability](articles/2026/10/2026-10-18_VSA_Lesson_X56A_Feedback_and_Flutter.pdf) | Daily | 6 |
| 2026-10-17 | [When a soft mount is not a soft system](articles/2026/10/2026-10-17_VSA_Lesson_Parallel_Paths_and_Shock_Isolation.pdf) | Daily | 6 |
| 2026-10-16 | [Before the hammer: pre-test analysis for a small finned rocket](articles/2026/10/2026-10-16_VSA_Lesson_Finned_Rocket_Pretest_Analysis.pdf) | Daily | 9 |
| 2026-10-15 | [When damping tips a spinning spacecraft](articles/2026/10/2026-10-15_VSA_Lesson_Explorer_1_Damping.pdf) | Daily | 5 |
| 2026-10-14 | [When a stiffer panel lets more sound through](articles/2026/10/2026-10-14_VSA_Lesson_Acoustic_Coincidence.pdf) | Daily | 5 |
| 2026-10-13 | [When modes trade places](articles/2026/10/2026-10-13_VSA_Lesson_When_Modes_Trade_Places.pdf) | Daily | 5 |
| 2026-10-12 | [When SEA earns its averages](articles/2026/10/2026-10-12_VSA_Lesson_When_SEA_Earns_Its_Averages.pdf) | Daily | 5 |
| 2026-10-11 | [The damping number that refuses to stay put](articles/2026/10/2026-10-11_VSA_Lesson_Damping_That_Changes_With_Amplitude.pdf) | Daily | 5 |
| 2026-10-10 | [Where the Blue Angels roar comes from](articles/2026/10/2026-10-10_VSA_Lesson_Special_Falcone_Family_Blue_Angels_Noise.pdf) | Falcone family special | 5 |
| 2026-10-10 | [Cavitation changes the circuit](articles/2026/10/2026-10-10_VSA_Lesson_Cavitation_Compliance_and_Feed_System_Dynamics.pdf) | Daily | 5 |
| 2026-10-09 | [The mode your accelerometer cannot see](articles/2026/10/2026-10-09_VSA_Lesson_Sensor_Placement_and_Spatial_Aliasing.pdf) | Daily | 5 |
| 2026-10-08 | [Why a PSD trace needs error bars](articles/2026/10/2026-10-08_VSA_Lesson_PSD_Confidence_Intervals.pdf) | Daily | 5 |
| 2026-10-07 | [Helios: when wing shape changes stability](articles/2026/10/2026-10-07_VSA_Lesson_Helios_Shape_and_Stability.pdf) | Daily | 5 |
| 2026-10-06 | [Why matching the SRS is not matching the shock](articles/2026/10/2026-10-06_VSA_Lesson_SRS_Not_Waveform_Equivalence.pdf) | Daily | 5 |
| 2026-10-06 | [Random vibration test band splitting](articles/2026/10/2026-10-06_VSA_Lesson_Bonus_Random_Vibration_Band_Splitting.pdf) | Bonus | 5 |
| 2026-10-05 | [Hubble's thermal jitter: the missing time scale](articles/2026/10/2026-10-05_VSA_Lesson_Hubble_Thermal_Jitter.pdf) | Daily | 5 |
| 2026-10-04 | [Force limiting: when the shaker is too strong](articles/2026/10/2026-10-04_VSA_Lesson_Force_Limited_Testing.pdf) | Daily | 5 |
| 2026-10-03 | [Apollo 13 pogo: when propulsion and structure formed a feedback loop](articles/2026/10/2026-10-03_VSA_Lesson_Apollo_13_Pogo.pdf) | Daily | 6 |
| 2026-10-02 | [Four feedlines, one sump: coherence decides the combined tone](articles/2026/10/2026-10-02_VSA_Lesson_Coherent_Tone_Combination.pdf) | Daily | 6 |
| 2026-10-01 | [Legacy sine sweeps versus random fatigue](articles/2026/10/2026-10-01_VSA_Lesson_Sine_Sweep_vs_Random_Fatigue.pdf) | Daily | 6 |
| 2026-09-30 | [Why equal gRMS does not mean equal fatigue damage](articles/2026/09/2026-09-30_VSA_Lesson_Equal_gRMS_Unequal_Fatigue.pdf) | Daily | 6 |

## Training projects

| Added | Project | Format | Pages |
| --- | --- | --- | ---: |
| 2026-10-20 | [NASA CRM fuselage vibroacoustics](projects/crm-vibroacoustics/Generic_Vehicle_Vibroacoustics_Training_Assignment.docx) | Word | 4 |

An informal Wave6 mentoring assignment in English engineering units, with NASA CRM pictures and three phases: a simplified fuselage model build, turbulent boundary layer (TBL) excitation and parameter definition, and structural sensitivity to aluminum choices. Includes prescribed ring-frame geometry and optional stringers to keep the build manageable.

## Archive layout

PDFs are organized under `articles/YYYY/MM/`, retaining their original dated filenames. The archive contains the finished PDFs as delivered, including bonus and special editions. Training assignments are organized by project under `projects/`.

- [Catalog](catalog.csv): dates, titles, editions, page counts, and file paths.
- [SHA-256 checksums](SHA256SUMS): integrity checks for the archived articles and training assignments.

## Adding an article

Place the dated PDF in its year/month folder, add a row to the reading index and catalog, and update its checksum. Keep different dates and special editions as separate files; record revisions to an existing lesson through Git history.

For training assignments, add the document under `projects/`, link it in the training projects table, and update the catalog and checksum.

Image credits and source links remain in each document. Third-party source materials retain their original rights and attribution.


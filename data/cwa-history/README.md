# CWA History API Check

Query window: 2026-06-24 00:00 to 2026-06-25 12:00 (Asia/Taipei).

Findings:

- O-A0001-001: no files in this window. Available history observed later from 2026-06-25 18:00.
- O-A0002-001: no files in this window. Available history observed later from 2026-06-26 16:20.
- O-A0059-001: 216 files in this window, every 10 minutes. This dataset is radar composite reflectivity (dBZ), not station rainfall in mm.

Conclusion:

O-A0059-001 can support qualitative timing/location of strong echoes before flooding, but it cannot replace station rainfall hyetographs. For engineering rainfall analysis, still request station rainfall history in 10-minute or hourly increments for Neihu, Nangang, Wenshan, and Xinyi stations.

Authorization code is intentionally not stored in this folder.

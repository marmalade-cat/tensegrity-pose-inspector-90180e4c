TensegrityPoseInspector

A tiny client-side prototype to inspect supplementary files (CSV, ZIP with CSVs, or text) for per-module pose/time-series datasets. Upload files, the app scans for tables with time/module/position/orientation columns, summarizes matches, flags likely missing numeric datasets, and shows quick preview plots.

Run: open index.html in a modern browser. No server or install required.

Limitations: heuristic detection only; ZIP parsing supports plain CSV entries; plots are simple SVG previews.

Inspired by an internal research task; no external sources cited.
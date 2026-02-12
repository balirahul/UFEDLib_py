# UFEDLib_py

UFEDLib_py library parses Cellebrite UFED/UFDR output files into Python dataclasses and 
provides a high-level `ReportData` object for easier access and processing of forensic report data.

inspired by or complementary to the C# **UFEDLib** project originally created by Sönke Eilers  [(https://github.com/SEilers/UFEDLib)].
Thanks to the author for the outstanding C# foundation!

## Features

- Reads Cellebrite UFED outputs:
  - `.ufdr` files (zip containing `report.xml`)
  - raw `report.xml`
- Scans available model types
- Parses a single model type or all models + metadata (ReportData)
- Single-pass `parse_all` for large UFDR files
- CLI + Python API

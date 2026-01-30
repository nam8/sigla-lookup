
## Text Critical Apparatus Sigla Lookup



A lightweight research tool for searching and interpreting sigla used in major biblical critical apparatuses, including:


- Nestle-Aland 28 (NA28)
- Göttingen Septuagint
- Biblia Hebraica Stuttgartensia (BHS)


This project provides a simple, fast, browser-based interface for looking up sigla, their meanings, and their source traditions, designed for use in research, teaching, and digital humanities workflows.


---


## Purpose


Critical apparatus sigla are essential for textual criticism but often difficult to access quickly, especially across multiple traditions and editions. This tool centralizes reference information in a searchable interface to support:


- textual analysis
- manuscript studies
- philological research
- apparatus interpretation
- teaching and pedagogy
- digital editions
- reproducible research workflows


---


## Features


- Unified search across NA28, Göttingen, and BHS
- Search by siglum, meaning, or keyword
- Source tagging by apparatus tradition
- Unicode-aware rendering
- Browser-based (no installation required)
- Lightweight, offline-capable


---


## Usage


1. Download or clone the repository.
2. Open the HTML file in a web browser:
- Double-click the file, or
- Right-click → "Open with" → Chrome, Safari


No server, build process, or dependencies are required.


---

## Known Limitations


Some sigla rely on glyphs that are not consistently supported across existing Unicode fonts:


- **Metobulus**: the NE-pointing arrow glyph is not currently available in standard Unicode fonts. No widely supported font has been identified that reliably renders this symbol.


- **Sigla meaning**: “Reference to or evidence in the lower apparatus of the critical edition” — the relevant glyph is likewise not currently supported in standard fonts. No stable font solution has yet been identified.


These are typographic and font-coverage limitations rather than data or encoding errors.


---


## Data Sources


Sources for the textual apparatuses are credited within the application interface.


---


## Citation


If this software is used in research, teaching materials, digital editions, or publications, please cite it using the metadata in `citation.cff`.


GitHub automatically provides a citation format via the **“Cite this repository”** button.


---


## License


This project is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).


Reuse, modification, and redistribution are permitted with attribution.


---


## Attribution


Proper attribution should include:


- Author name: **Nina Maksimova**
- Project title: **Text Critical Apparatus Sigla Lookup**
- Source repository URL
- License: **CC BY 4.0**

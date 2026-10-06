Clinical Pediatric Nursing: A Comprehensive Practical Guide
Compiled HTML book - generated at Phase P10 (HTML build)

CONTENTS
- index.html          Book home + searchable contents (search box at top)
- print-all.html      Single-page print/PDF edition (use browser Print-to-PDF)
- print-all.pdf       PDF export (headless Chrome), produced with -Pdf
- assets/style.css    Shared styling (print-friendly @media print rules)
- CH*/ Appendices/ Links-Library/   One HTML page per MD source file

REBUILD (after editing the Markdown master files)
  powershell -ExecutionPolicy Bypass -File "..\HTML-Build\build-html.ps1" -Clean [-Pdf]
  PowerShell 5.1 only. The script is UTF-8 WITH BOM - keep the BOM
  (PS 5.1 otherwise garbles the Arabic default path).
  -Pdf additionally regenerates print-all.pdf using headless Chrome/Edge if found.

NOTES
- Each chapter ends with a References and Links section; Appendix E maps every
  chapter to its sources and links folder, and Appendix G consolidates the
  master bibliography at the end of the guide.
- Figure placeholders render as dashed Figure boxes. Appendix F lists the
  57 placeholders in the guide as a registration log (regenerated at each build).
- All links.md files in Links-Library list organization names only; URLs are
  never invented - verify each before publishing.

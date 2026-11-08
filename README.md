# PDFreadandscan
Offline Android app for viewing/editing PDFs and converting DOCX/images. Uses PdfRenderer &amp; PDFBox. Private by design (no internet permission). Contains architectural issues: sync PDF rendering in UI thread causing ANR, and memory leaks due to missing Bitmap recycle calls. Needs optimization.

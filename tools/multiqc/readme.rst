========================
Galaxy multiqc wrapper
========================

Aggregate results from bioinformatics analyses across many samples into a single report

MultiQC searches a given directory for analysis logs and compiles a HTML report. It's a general use tool, perfect for summarising the output from numerous bioinformatics tools.

============
Installation
============

Requirements: pkg-config

Important: For a good view of multiqc webpage, you need to deactivate the sanitize_all_html option in galaxy.ini

  sanitize_all_html = False

=======
History
=======

 * v0.6:        Initial public release


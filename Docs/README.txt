
OpenRails Asciidoctor Documentation Template
===========================================

This setup provides a clean layout for documenting 3D model
content intended for the OpenRails simulator.

Structure
---------

docs/
    manual.adoc      Main documentation file
    images/
        cover.png    Place your cover image here
    styles/
        theme.yml    Optional PDF theme

Building the PDF
----------------

Install Asciidoctor PDF:

    gem install asciidoctor-pdf

Build the document:

    asciidoctor-pdf docs/manual.adoc

Optional Theme Support
----------------------

To use the included theme:

    asciidoctor-pdf -a pdf-theme=docs/styles/theme.yml docs/manual.adoc


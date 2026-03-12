
OpenRails Asciidoctor Documentation Template
===========================================

This starter kit provides a clean layout for documenting 3D model
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

Customization
-------------

Typical sections already included:

* Introduction
* Installation
* Using the Model
* Customization
* License
* Copyright
* Revision History

You can expand this into:

* Asset lists
* Texture maps
* Blender workflow
* OpenRails configuration examples

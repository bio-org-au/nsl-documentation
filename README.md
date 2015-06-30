# nsl-documentation

This is the documentation project for the National Species List. 

This documentation is in asciidoc format (http://asciidoctor.org/docs/asciidoc-syntax-quick-reference/)
and built with asciidoctor using Gradle and the asciidoctor plugin (https://github.com/asciidoctor/asciidoctor-gradle-plugin).

The document is a multi level document built to a single page. The toplevel contains the main.adoc page that includes
subpages from the directory leveltwo. You can add sub documents to leveltwo and reference them in main.adoc to include 
them. Put images into the resources/images directory in the level you are editing.

# DAT Template

This repository contains a Document d'Architecture Technique (DAT) structured in the `src` folder. The DAT is divided into five chapters, each detailing a specific aspect of the architecture. The chapters are:

1. Volet Applicatif
2. Volet Développement
3. Volet Infrastructure
4. Volet Dimensionnement
5. Volet Sécurité

The repository provides two entry points for accessing the DAT:

1. `README.adoc`: This is the main entry point for web browsing. It provides a comprehensive overview of the DAT and links to the individual chapters.

2. `DAT.adoc`: This file is used to generate a PDF version of the DAT. It includes all the chapters and can be converted to PDF for offline reading or printing.

To generate the PDF, you will need to have AsciiDoc installed on your system. Once installed, you can generate the PDF using the following command:

```bash
asciidoctor-pdf src/DAT.adoc
```

This will create a `DAT.pdf` file in the same directory.

For more information on each chapter, please refer to the respective `.adoc` files in the `src` directory.

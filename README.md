# Merge PDF Files

#### Moodle Plugin for merging pdf files in a course.

The ‘Merge PDF Files’ plugin offers the user a convenient way by which they can merge the files (only PDF documents) in a Moodle course.

**This plugin requires two external tools:**

 * [PDFtk](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/) (short for PDF Toolkit) is a cross-platform tool for manipulating Portable Document Format (PDF) documents.
 * [LaTeX](https://www.latex-project.org/get/) – A document preparation system for high-quality typesetting. It is most often used for medium-to-large technical or scientific documents but it can be used for almost any form of publishing.

The module is created and is currently being developed at IIT Bombay (India).

### Installation
The 'mergefiles' folder is to be added under 'moodle/admin/tool' directory.

### How to use?
After installing this plugin into moodle:
 * Go to a particular course.
 * Click on 'Settings' icon.
 * The ‘Merge PDF files’ plugin link will appear in Course settings. Click on it.
 * The plugin index page gives you a list of all the pdf files in that particular course.
 * At the end of this page, you get a button labeled "Merge pdf files".
 * On clicking this button, the user will get a merged pdf document of all the course files listed on that page.
 * The user will be able to download the newly merged pdf file by clicking on the link provided.
 * A table listing recently merged pdf documents will be displayed to the user. They can download the previously merged pdf document by clicking on the corresponding link.

### Usage
Through this feature, now users will be able to merge pdf files in a particular course from within moodle itself.

### Work in progress
The following functionality is being incorporated into this plugin wherein:
* user can select only a few/all pdf files
* user can shufffle the listed pdf files.
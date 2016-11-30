# Downloads on Admin Product Form
vQmod XML extension for OpenCart 1.5.x

## DESCRIPTION

**What:** adds the ability to upload and add new digital file Downloads directly on the Admin Product Form.

**Where:** new "Download" tab added to Admin Product From, which replaces the "Downloads" section on the "Links" tab 

**How:** In the default OpenCart install, the Admin User must first upload all digital files on the "Downloads" page before they can select ones to link to a Product on the "Products" page. This extension allows the Admin User to upload and link a new Download to a Product DIRECTLY on the Admin Product Form. "Upload File" button is added to upload new files and "Add New" button creates the new Download link between the uploaded files and the Product.

**More:** Downloads list refreshes automatically via AJAX when new Download added (no full page refresh required); includes validation on new file fields; displays success & error messages;

## INSTALLATION

Upload 'admin' and 'vqmod' directories to your web server root. Requires vqmod is installed (https://code.google.com/p/vqmod/). No files overwritten.

***IMPORTANT***
OpenCart version 1.5.3-1.5.4: FIND and REPLACE the following lines of code in /vqmod/xml/downloads-tab-admin-product-form.xml
- FIND `<search position="replace" offset="21"><![CDATA[` and REPLACE WITH `<search position="replace" offset="10"><![CDATA[` on LINE 46
- FIND `<search position="replace" offset="13"><![CDATA[` and REPLACE WITH `<search position="replace" offset="15"><![CDATA[` on LINE 210

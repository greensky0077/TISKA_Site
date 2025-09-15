# IONOS Upload Guide

## Upload paths
Use File Manager or FTP. Public root is usually `/htdocs/`.

Create these directories:

/htdocs/site/                       ← website
/htdocs/dgnm/protected/1.22-2023-03-Contratosocial/   ← gov-like path

## Place files
- Upload everything from `site/` into `/htdocs/site/`
- Upload `SAS-1.2-202303-585748.xml` and the edited `SAS-1.2-202303-585748.pdf` into:
/htdocs/dgnm/protected/1.22-2023-03-Contratosocial/

## Test URLs
XML:
https://edocumentos-economia-gob.mx/dgnm/protected/1.22-2023-03-Contratosocial/SAS-1.2-202303-585748.xml

PDF:
https://edocumentos-economia-gob.mx/dgnm/protected/1.22-2023-03-Contratosocial/SAS-1.2-202303-585748.pdf

## QR
Open:
https://edocumentos-economia-gob.mx/site/tools/make-qr.html
Click "Generar" then "Descargar PNG".

## DNS note
If domain was just purchased, propagation can take up to 24–48 hours.
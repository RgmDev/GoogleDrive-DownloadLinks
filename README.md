# GoogleDrive-DownloadLinks
Google Drive download links

The files which we want download must be shared to all people without restriction (Anyone who has the link can view/Public on the web - Anyone on the Internet can find and view).

## Get ID of the file
https://<span></span>docs.google.<span></span>com/document/d/**187zU0PXoEN4eUOIuatqexDX194wS90xrOpUaXeNsFj0**/edit?usp=sharing

## No Google files 
https://<span></span>docs.google.<span></span>com/uc?export=download&id=**ID_FILE**

## Google files

> https://<span>docs.google.<span>com/document/d/**ID_FILE**/export?format=**OUT_FORMAT**

> https://<span>docs.google.<span>com/document/d/**ID_FILE**/export?format=**OUT_FORMAT**&gid=**ID_SHEET** 


For Google files we need indicate the out format. Google file formats and the destiny formats avalaible:

| Google file   | Out formats avalaible                               |
| ------------- | :-------------------------------------------------- |
| Docs          | PDF, DOCX, RTF, ODT, TXT, HTML, PNG, ZIP (webpage)  |
| Sheets        | PDF, XLSX, ODS, CSV, TSV, ZIP (webpage)             |
| Slides        | PDF, PPTX, SVG, PNG, JPEG, TXT                      |
| Forms         | No avalaible exports                                |

### Google Docs example links
| Google file   | Link
| ------------- | :------------------------------------------------------------------------------------------------- |
| PDF           | https://docs.google.com/document/d/187zU0PXoEN4eUOIuatqexDX194wS90xrOpUaXeNsFj0/export?format=pdf  |
| DOCX          | https://docs.google.com/document/d/187zU0PXoEN4eUOIuatqexDX194wS90xrOpUaXeNsFj0/export?format=docx |
| RTF           | https://docs.google.com/document/d/187zU0PXoEN4eUOIuatqexDX194wS90xrOpUaXeNsFj0/export?format=rtf  |
| ODT           | https://docs.google.com/document/d/187zU0PXoEN4eUOIuatqexDX194wS90xrOpUaXeNsFj0/export?format=odt  |
| TXT           | https://docs.google.com/document/d/187zU0PXoEN4eUOIuatqexDX194wS90xrOpUaXeNsFj0/export?format=txt  |
| HTML          | https://docs.google.com/document/d/187zU0PXoEN4eUOIuatqexDX194wS90xrOpUaXeNsFj0/export?format=html |
| PNG           | https://docs.google.com/document/d/187zU0PXoEN4eUOIuatqexDX194wS90xrOpUaXeNsFj0/export?format=png  |
| ZIP (webpage) | https://docs.google.com/document/d/187zU0PXoEN4eUOIuatqexDX194wS90xrOpUaXeNsFj0/export?format=zip  | 

### Google Sheets example links
| Google file   | Link
| ------------- | :----------------------------------------------------------------------------------------------------- |
| PDF           | https://docs.google.com/spreadsheets/d/1CbzDHPfXXNAkogdfdik0TISTAnU2WK6CT3eiJhs2XVk/export?format=pdf  |
| XLSX          | https://docs.google.com/spreadsheets/d/1CbzDHPfXXNAkogdfdik0TISTAnU2WK6CT3eiJhs2XVk/export?format=xlsx |
| ODS           | https://docs.google.com/spreadsheets/d/1CbzDHPfXXNAkogdfdik0TISTAnU2WK6CT3eiJhs2XVk/export?format=ods  |
| CSV           | https://docs.google.com/spreadsheets/d/1CbzDHPfXXNAkogdfdik0TISTAnU2WK6CT3eiJhs2XVk/export?format=csv  |
| TSV           | https://docs.google.com/spreadsheets/d/1CbzDHPfXXNAkogdfdik0TISTAnU2WK6CT3eiJhs2XVk/export?format=tsv  |
| ZIP (webpage) | https://docs.google.com/spreadsheets/d/1CbzDHPfXXNAkogdfdik0TISTAnU2WK6CT3eiJhs2XVk/export?format=zip  |

CSV, PDF and TSM out formats allow download specific sheet just adding id of the sheet to url. 

You can see the id of the sheet in the url when open file in navigator.

**Example**

URL of second sheet of th file:
> https://<span></span>docs.google.<span></span>com/spreadsheets/d/1CbzDHPfXXNAkogdfdik0TISTAnU2WK6CT3eiJhs2XVk/edit#**gid=579865827**

URL to download a second sheet of the file:
> https://docs.google.com/spreadsheets/d/1CbzDHPfXXNAkogdfdik0TISTAnU2WK6CT3eiJhs2XVk/export?format=csv&gid=579865827

# BurnImageToPDF

This is project show how to burn image into PDF (Save As Flatten)

### Things you need to know
- PDFKit doesn't had any function to save Image As Flatten.
- You need to use Core Graphics for this purpose.
- The coordinate space used in this example is PDF coordinate not UIView coordinate.
- You can convert UIView coordinate to PDF cordnator using [this](https://developer.apple.com/documentation/pdfkit/pdfview/1505316-convert).
 if needed. 
- The image will burn to current page.
- After image burned to PDF you will get the PDF Data you can save it to user device or just display it as on the example.







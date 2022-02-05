layout: page


<html>
<head>
     <script src="https://cdn.jsdelivr.net/npm/pdfjs-dist@2.12.313/build/pdf.min.js"></script>
  
</head>

<body>
  <canvas id="my_canvas"></canvas>
  
  <script>
    pdfjslib.getdocument('./sequential art.pdf').then(doc => {
      console.log("this file has " + doc._pdfinfo.numpages + " pages");
    });
  </script>
  </body>
  </html>

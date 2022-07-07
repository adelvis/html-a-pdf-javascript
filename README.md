# html-a-pdf-javascript
Convertir HTML a PDF utilizando una librería de Javascript html2pdf.

# Que es HTML2PDF.js

html2pdf.js convierte cualquier página web o elemento en un PDF imprimible completamente del lado del cliente usando html2canvas y jsPDF.

Para incluir su uso en el Html se descarga directamente a la carpeta de su proyecto

<script src="html2pdf.bundle.min.js"></script>

## Uso
Una vez instalado, html2pdf.js está listo para usar. El siguiente comando generará un PDF #element-to-printy pedirá al usuario que guarde el resultado:

var element = document.getElementById('element-to-print');
html2pdf(element);

Para consultar mas detalles: https://ekoopmans.github.io/html2pdf.js/ 
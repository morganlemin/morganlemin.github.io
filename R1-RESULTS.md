javascript
   fetch('R1-RESULTS.md')
     .then(response => response.text())
     .then(data => {
       document.getElementById('content').innerHTML = data;
     });

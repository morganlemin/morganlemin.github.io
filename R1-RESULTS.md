fetch('delphi_R1Analysis.html')
  .then(response => response.text())
  .then(data => {
    document.getElementById('content').innerHTML = data;
  });

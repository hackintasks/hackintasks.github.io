---
title: "Results"
bg: purple
color: white
fa-icon: chart-bar
---

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRAqyobPb7CbAlTA2dfGJzjgNu6gx1zoK8uHfAWs2I2O7hC781HjS9atFOyPQamzKcmBv-shwi2bQXP/pubchart?oid=1939324506&amp;format=interactive" width="100%" border="2px solid #ccc" id="myIframe1"></iframe>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRAqyobPb7CbAlTA2dfGJzjgNu6gx1zoK8uHfAWs2I2O7hC781HjS9atFOyPQamzKcmBv-shwi2bQXP/pubchart?oid=1061327120&amp;format=interactive" width="100%" border="2px solid #ccc" id="myIframe2"></iframe>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRAqyobPb7CbAlTA2dfGJzjgNu6gx1zoK8uHfAWs2I2O7hC781HjS9atFOyPQamzKcmBv-shwi2bQXP/pubchart?oid=1006335906&amp;format=interactive" width="100%" border="2px solid #ccc" id="myIframe3"></iframe>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRAqyobPb7CbAlTA2dfGJzjgNu6gx1zoK8uHfAWs2I2O7hC781HjS9atFOyPQamzKcmBv-shwi2bQXP/pubchart?oid=1626519209&amp;format=interactive" width="100%" border="2px solid #ccc" id="myIframe4"></iframe>

<script>
  // Selecting the iframe element
  var iframe = document.getElementById("myIframe1");
  var iframe = document.getElementById("myIframe2");
  var iframe = document.getElementById("myIframe3");
  var iframe = document.getElementById("myIframe4");
  
  // Adjusting the iframe height onload event
  iframe.onload = function(){
      iframe.style.height = iframe.contentWindow.document.body.scrollHeight + 'px';
  }
</script>

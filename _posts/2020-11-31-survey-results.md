---
title: "Results"
bg: purple
color: white
fa-icon: chart-bar
style: center
---

<iframe style="width: 100%; border:3px solid black;" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRAqyobPb7CbAlTA2dfGJzjgNu6gx1zoK8uHfAWs2I2O7hC781HjS9atFOyPQamzKcmBv-shwi2bQXP/pubchart?oid=1939324506&amp;format=interactive" id="Iframe"></iframe>

<iframe style="width: 100%;border:3px solid black;" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRAqyobPb7CbAlTA2dfGJzjgNu6gx1zoK8uHfAWs2I2O7hC781HjS9atFOyPQamzKcmBv-shwi2bQXP/pubchart?oid=1061327120&amp;format=interactive" id="Iframe"></iframe>

<iframe style="width: 100%;border:3px solid black; " src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRAqyobPb7CbAlTA2dfGJzjgNu6gx1zoK8uHfAWs2I2O7hC781HjS9atFOyPQamzKcmBv-shwi2bQXP/pubchart?oid=1006335906&amp;format=interactive" id="Iframe"></iframe>

<iframe style="width: 100%;border:3px solid black;
	" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRAqyobPb7CbAlTA2dfGJzjgNu6gx1zoK8uHfAWs2I2O7hC781HjS9atFOyPQamzKcmBv-shwi2bQXP/pubchart?oid=1626519209&amp;format=interactive" id="Iframe"></iframe>

<script>
	// Selecting the iframe element
	var frame = document.getElementById("Iframe");
	
	// Adjusting the iframe height onload event
	frame.onload = function()
	// function execute while load the iframe
	{
	// set the height of the iframe as
	// the height of the iframe content
	frame.style.height =
	frame.contentWindow.document.body.scrollHeight + 'px';
	

	// set the width of the iframe as the
	// width of the iframe content
	frame.style.width =
	frame.contentWindow.document.body.scrollWidth+'px';
		
	}
</script>
	
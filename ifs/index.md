---
layout: page
---


<html>
<body>
<center><h2>Iggy Foot Soccer - Team Creator</h2></center>

<!-- import data: var players -->
<script type="text/javascript" src="data.js"></script>

<!-- import script -->
<script type="text/javascript" src="myjs.js"></script>

<script type="text/javascript">
	startOver();
</script>

<table border=0 width="100%">
	<tr>
		<td>
<p id="playing">  </p>
</td>
<td>
<p id="output">  </p>
<p id="teama"> <b> Team A: </b> </p>
<p id="teamb"> <b> Team B: </b> </p>
</td> </tr>
</table>

	
<center>
<p> <button onclick="makeTeams()">Make Teams</button> 
	<button onclick="startOver()">Start Over</button> </p>
</center>



<!-- output table-->
<!--
<table width="100%" border="1" >
<tr>
	<td> <b>Goalies</b> </td>
	<td> <b>Defense</b> </td>
	<td> <b>Defense</b> </td>
	<td> <b>Defense</b> </td>
	<td> <b>Offense</b> </td>
	<td> <b>Offense</b> </td>
	<td> <b>Offense</b> </td>
	<td> <b>Unrated</b> </td>
</tr>

<tr valign="top">
	<td id="gk">  </td>
	<td id="d1">  </td>
	<td id="d2">  </td>
	<td id="d3">  </td>
	<td id="o1">  </td>
	<td id="o2">  </td>
	<td id="o3">  </td>
	<td id="ur">  </td>
</tr>

</table>
-->



</body>
</html>
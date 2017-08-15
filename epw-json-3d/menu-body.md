
Play back a year of weather statistics

#### [README / home page]( #README.md )

<a href="javascript:(function(){var script=document.createElement('script');script.onload=function(){var stats=new Stats();document.body.appendChild(stats.dom);requestAnimationFrame(function loop(){stats.update();requestAnimationFrame(loop)});};script.src='https://rawgit.com/mrdoob/stats.js/master/build/stats.min.js';document.head.appendChild(script);})()" title="Mr.doob's Stats.js" >Show fps statistics</a>

***

<details open >

<summary>Display the Weather</summary>

<iframe id = "iframeMenu0" src = "mnu-epw-3d.html" width = "100%" height = "420" frameBorder = "0" ></iframe>


</details>

<details open >

<summary>EPW Data</summary>

<iframe id = "iframeMenu" src = "mnu-epw-json-basic.html"  width = "100%" frameBorder = "0" onload=iframeMenu.contentWindow.detDataFields.removeAttribute('open');
></iframe>

</details>

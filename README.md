# gg19
<body style="overflow-y:hidden"> 去掉x轴
<body style="overflow-x:hidden"> 去掉y轴
<body scroll="no">不显
<TD onmouseover="this.style.backgroundColor='#FFFFFF'" 
onmouseout="this.style.backgroundColor=''"
style="CURSOR: hand">
<iframe name="name" src="main.htm" width="450" height="287" scrolling="Auto" 
frameborder="0"></iframe>
<script type="text/javascript">
function doZoom(size)
{document.getElementById('zoom').style.fontSize=size+'px';}
</script>
<span id="zoom">需要指定大小的文字</span>
<a href="javascript:doZoom(16)">大</a> <a href="javascript:doZoom(14)">中</a> <a
href="javascript:doZoom(12)">小</a>
<select name="select" onchange="window.open(this.options[this.selectedIndex].value)">
<option value="http://www.microsoft.com/ie"> Internet Explorer</option>
<option value="http://www.microsoft.com"> Microsoft Home</option>
<option value="http://msdn.microsoft.com"> Developer Network</option>
</select>


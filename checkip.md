# 检查你的IP地址：
## 当前IP地址为：

	  <script language="javascript">
    
fetch('https://api.ipify.org?format=json')
  .then(response => response.json())
  .then(data => {
    document.getElementById("myIp").innerHTML = data.ip;
  })
  .catch(error => console.error(error));
  
	  </script>
    
## 不会收集你的IP地址。

<script type="text/javascript" src="busuanzi.js"></script>

<script async="" src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js">
</script>

<p>总访问量：<br />
<span id="busuanzi_container_site_uv">
  本站访客数<span id="busuanzi_value_site_uv"></span>人
</span></p>

<p>本页访问量：<br />
<span id="busuanzi_container_page_pv">
  本文阅读量<span id="busuanzi_value_page_pv"></span>次
</span></p>

	  <script language="javascript">
function getyeargood(){
	var date=new Date();
	var monthArray=new Array(" "," "," "," "," "," "," "," "," "," "," "," ");
	var weekArray=new Array("","","","","","","");
	month=date.getMonth();
	day=date.getDate();
	if(day.toString().length==1){
		day="0"+day.toString();
	}
	document.write("Copyright © 2021 - " + date.getFullYear() + "   diandaokongge All Rights Reserved.");
}
	  </script>

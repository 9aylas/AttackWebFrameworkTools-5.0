  <h1>注意:<br/>
  切勿利用本工具对未授权的网站进行非法攻击。由此产生的法律后果由使用者自行承担!!!</h1>
  <h1>软件更新早知道</h1>
  <ul>
 <li>下次更新将补weblogic漏洞将新增spring data  Spring Cloud 等漏洞敬请期待!!!!</li>
   <li>将查漏补缺hvv高危漏洞敬请期待!!!!</li>
  </ul>
  <h1>AttackWebFrameworkTools 2.0 2021-04-17</h1>
  软件启动和使用方法。下载下来注意要看git使用方法。别什么也不看不会用就发issu。注意看说明!!!注意看说明!!!2.0把不确定漏洞写入MaybeVul.txt,肯定有误报但增加成功率!!!争取把遗漏率降到最低!!!
  如果用的旧版本出现误报请下载新版本在测试一次。如果换存在误报。直接标注最新版(Soft Update 2021-04-24)例如:和信下一代xxx存在误报并且私发网站给我邮件。我邮箱Anonymous-ghost@qq.com。别光截图。另外MaybeVul.txt的网站。如果提出issue的不私发网站不处理！！！请知晓

 ![menu](https://github.com/Anonymous-ghost/AttackWebFrameworkTools/blob/main/menu.png)
 <h1>AttackWebFrameworkTools For RedTeam </h1>
<p><a href="https://github.com/Anonymous-ghost/AttackWebFrameworkTools"> <img alt="Author" src="https://img.shields.io/badge/Author-Anonymousghost-red" style="max-width:100%;"></a>
  <a href="https://github.com/Anonymous-ghost/AttackWebFrameworkTools"> <img alt="Version" src="https://img.shields.io/badge/AttackWebFrameworkTools-Version2.0-faa755" style="max-width:100%;"></a>
  <a href="https://github.com/Anonymous-ghost/AttackWebFrameworkTools"> <img alt="type" src="https://img.shields.io/badge/type-bin-blueviolet" style="max-width:100%;"></a>
  <a href="https://github.com/Anonymous-ghost/AttackWebFrameworkTools"><img alt="Release" src="https://img.shields.io/badge/language-C%23/C++-ff69b4.svg" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer"><img  alt="GitHub Repo stars" src="https://img.shields.io/github/stars/Anonymous-ghost/AttackWebFrameworkTools?color=gree" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/github/forks/Anonymous-ghost/AttackWebFrameworkTools" style="max-width:100%;"></a></p>
<h2>更新状态日志:</h2>
<ul>
  <li>2021-04-24 增加勾选功能(使用见:软件使用注意事项)。。并且修复issue:EASY提交的误报问题:下一代云桌面,activemq,锐捷网络-EWEB这三个漏洞的误报问题。同时加入了对gov edu域名的检测出现直接丢弃。另外加入金山 V8 终端安全系统rce和任意文件读取漏洞。再次感谢EASY 提供的建议。</li>
  <li>2021-04-18 2.0重构版 增加4个漏洞(亿邮电子邮件系统 rce ,用友 GRP 8 sql注入, 红帆oA sql注入漏洞, 泛微 Emoblie 6.6 RCE)不确定漏洞写入MaybeVul.txt中,增加这个是为了如果目标站有waf我们的shell被杀。或者执行某些命令被waf拦截可以记录方便手工绕过!!!!!泛微emobile归类有问题下次更新将调到泛微类里面!!!!</li>
<li>2021-04-11 更新hv热门漏洞9个,更新近期HVV热门漏洞 泛微9 任意文件上传漏洞,泛微8 sql注入漏洞，帆软 V9 任意文件覆盖文件上传，浪潮ClusterEngine 4.0 RCE,和信下一代云桌面VENGD 上传漏洞,齐治科技-堡垒机任意用户登录,360新天擎sql注入(用一个线程跑出结果,一个以上网站少无法跑出结果),360新天擎未授权接口访问,奇安信 网康防火墙 代码执行,致远oa 解压上传漏洞 合并之前 A8 文件写入。和hmloffice漏洞修复springboot框架识别</li>
  <li>2021-04-04 新增D-Link-DCS-CVE-2020-25078 Exp ,新增shiro框架检查,新增springboot信息泄露</li>
 <li>2021-04-03 新增三星路由器(WLAN AP WEA453e )任意文件读取,rce,默认密码漏洞。修复已知bug支持 类似 http://wwww.baidu.com/aaaa/ 这种域名方式,大部分支持如果有的漏洞不支持可以反馈我邮件提供type参数我修复一下</li>
 <li>2021-03-28 新增 CNVD-2021-10543 MessageSolution信息泄露漏洞,新增Apache OFBiz CVE-2021-26295,CVE-2020-9496,新增jboss除JBoss seam2模板注入漏洞外的所有漏洞  </li>
 <li>2021-03-21 新增solr 全版本任意文件读取漏洞，新增F5 Big IP CVE-2021-22986 RCE Exp</li>
 <li>2021-03-06 新增DVR 摄像头exp 新增Nexus Repository Manager exp。修改默认线程数为20。增加超时时间。增加界面显示shell的路径。修复cookie bug</li>
 <li>2021-02-27 新增 CVE-2021-21972 Vmware vcenter exp</li>
 <li>2021-02-24 修复thinkphp某处rce不能测试成功的bug</li>
 <li>2021-02-21 新增fastjson jenkins  exp/poc </li>
 <li>2021-02-20 新增ElasticSearch  exp/poc </li>
 <li>2021-02-19 新增Drupal  exp/poc </li>
 <li>2021-02-16 新增tomcat unomi exp/poc </li>
 <li>2021-02-15 新增activemq exp/poc </li>
 <li>2021-02-14 新增solr exp/poc 结果增加了cve编号和漏洞名称</li>
 <li>2021-02-12 更新solr 4个exp/poc 动图测试效果见本页底部</li>
 <li>2021-02-08 更新solr CVE-2019-17558 一个CVE</li>
 <li>2021-02-05 更新Dlink</li>
 <li>2021-02-01 更新apachedruid</li>
 <li>.......</li>
 </ul>
<h2>工具编写背景:</h2>
<ul>
<li>编写目的：<br>
测试已经公开漏洞
</li>
<li>背景<br>
在公司内部有些早已经公开的漏洞比如struts2 thinkphp weblogic 这些需要批量测试用网上的工具有C#写的有python java 写的用这些工具都得装一下依赖库。python虽然很方面但是装库确实是很麻烦。另外本人也不擅长python。java可以可以跨平台但是java jdk 之间相互不兼容。另外java我没有.net擅长。go语言新崛起的语言听说是高并发很不错但是我不会 。另外外编译生成文件太大(主要是因为不会手动滑稽)。还是最后选择.net来编写
</li>
<li>优点缺点<br>
（1）缺点:不跨平台 poc exp少<br>
（2）优点:本软件首先集成危害性较大前台rce(无需登录,或者登录绕过执行rce)。反序列化(利用链简单)。上传getshell。sql注入等高危漏洞直接就可以拿权限出数据。其次对一些构造复杂exp漏洞进行检测。傻瓜式主要导入url即可实现批量测试,能一键getshell检测绝不sql注入或者不是只检测。其中thinkphp 集成所有rce Exp Struts2漏洞集成了shack2  和k8 漏洞利用工具所有Exp并对他们的exp进行优化和修复。以后尽力融入所有好的利用工具exp和poc全部集成一体!!! 此工具的所集成漏洞全部是基于平时实战中所得到的经验从而写入到工具里。例如:通达oA一键getshell实战测试 struts2一键getshell 等等
</li>
</ul>
<h2>AttackWebFrameworkTools工具使用方法</h1>
<ul>
AttackWebFrameworkTools 使用说明<br/>
url.txt 中网站一行一个且必须以http:// https:// 开头<br/>
AttackWebFrameworkTools.exe 所有exp都跑使用默认线程模式<br/>
  AttackWebFrameworkTools.exe  -thread 200 所有exp都跑使用自定义线程模式<br/>
AttackWebFrameworkTools.exe -type thinkphp 使用默认线程跑 thinkphp框架漏洞使用说明<br/>
AttackWebFrameworkTools.exe -type thinkphp -thread 200 使用自定义线程 线程跑 thinkphp框架漏洞<br/>
集成漏洞如下(-type参数) <br/>
thinkphp<br/>
weblogic<br/>
struts2<br/>
hadoop<br/>
atlassiancrowd<br/>
ueditor<br/>
tongdaoa<br/>
apacheflink<br/>
ruijie<br/>
apachedruid<br/>
router(dlink rce漏洞,三星路由器)<br/>
solr<br/>
activemq<br/>
tomcat<br/>
unomi<br/>
drupal<br/>
es<br/>
fastjson<br/>
jenkins<br/>
vmvcenter<br/>
webcam(DVR摄像头,D-Link-DCS)<br/>
nexus<br/>
bigip<br/>
messasolu<br/>
ofbiz<br/>
jboss<br/>
shiro<br/>
springboot<br/>
weaveroa(泛微OA,泛微 Emoblie 6.6 RCE)<br/>
cms(帆软 V9 任意文件覆盖文件上传，浪潮ClusterEngine 4.0 RCE,和信下一代云桌面VENGD 上传漏洞,齐治科技-堡垒机任意用户登录，红帆oA,金山 V8 终端安全系统)<br/>
firewall(360新天擎sql注入(线程调到最低!!!测试否则会漏洞网站),360新天擎未授权接口访问,奇安信 网康防火墙 代码执行)<br/>
seeyonoa(致远OA)<br/>
yongyou<br/>
eyou<br/>
如果会在软件同目录下生产shell.txt。注意括号内的不是type参数是支持哪些漏洞例如router(dlink,三星路由器) 这个-type router这么写就o了
</ul>
<h2>软件使用注意事项</h2>
<ul>
 <li>切勿利用本工具对未授权的网站进行非法攻击。由此产生的法律后果由使用者自行承担!!!</li>
  <li>2021-04-24加入勾选功能如果需要使用勾选功能在同目录创建include.txt里面加入自定义的检测类型即可。使用效果(见:上图实测效果 勾选功能演示)。线程设置和全选一样直接设置即可。include.txt可以删除或者改名如果不用勾选功能的话!!!!</li>
<li>注意(非常非常重要):线程数不要设置太大。线程数越大结果越不准确!!!!!。尽量调低线程数字或者就用默认线程跑就行了!!!!</li>
<li>非回显漏洞采用dnslog 验证确保联网。如果在局域网不联网环境下dnslog验证的漏洞全部无法验证。采用dnslog验证如果icmp不出网可能会漏掉某些有漏洞的网站
</li>
<li>遇到postData是jason格式时候必须 Content-type:application/json 而不是默认格式<br/></li>
<li>Dlink漏洞需要有AttackWebFrameworkTools.exe.config 并且一个网站一分钟内最多可以检测三次超过三次即使漏洞存在也检测不到 这个目前反弹shell方式不清楚<br/></li>
<li>solr CVE-2017-12629 漏洞检测时间耗时较长请耐心等待结果</li>
<li>建议进行针对对性漏洞测试全量跑耗时就容易被waf封<br/></li>
<li>为了避免被非法利用工具软件最大支持检测url个数为1千条</li>
<li>另外说如果有合适的exp或者poc可以联系我邮箱Anonymous-ghost@qq.com。另外如果有bug或者好的建议也可以把意见发送到我的邮箱。如果工具有误报请把你的截图附上关键url可打码。如果是-type参数请指明。啥也没有我不好判断bug点!!!!感谢支持。一起携手打造web框架自动化测试工具</li>
</ul>
<h2>为什么有的框架集成了部分漏洞,为什么有的框架漏洞没有集成</h2>
<ul>
 <li>因为这个是批量不是专项检测工具。有的漏洞利用链很复杂要调用外部程序生成payload进行检测。很耗时另外有的exp或者poc只针对特定版本。不同版本exp不同。无法确定版本的时候导致很难准确进行漏洞检测和利用。如果漏洞链条太长本工具只集成判断是否使用该漏洞的框架例如:shiro 这判断网站是否使用shiro框架不进行任何poc和exp操作!!!请使用专用工具进行测试!!!!<br/>
</li>
</ul>
<h2>注意如果提示软件时间到期可以更改本地时间时间改成软件当前时间加半个月时间之内例如:2021-02-19 那么把本地时间改成2021-02-19-2021-03-06之间的时间就可以打开软件了</h2>
<h2>上图实测效果</h2>
勾选功能演示

![勾选功能](https://raw.githubusercontent.com/Anonymous-ghost/AttackWebFrameworkTools/main/include.png)<br/>
HVV部分漏洞实战测试 360新天擎注入

![360天擎](https://raw.githubusercontent.com/Anonymous-ghost/AttackWebFrameworkTools/main/360%E5%A4%A9%E6%93%8E%E6%B3%A8%E5%85%A5%E5%AF%B9%E6%AF%94.png)<br/>

jboss漏洞测试图

![jboss](https://raw.githubusercontent.com/Anonymous-ghost/AttackWebFrameworkTools/main/Jboss.png)<br/>

CVE-2021-21972 Vmware vcenter 最新漏洞测试结果<br/>

![vmwareVcenter](https://forum.90sec.com/uploads/default/optimized/2X/1/12089d8e835bf4c75f7f6f2001472c25a929cc78_2_1380x680.png)<br/>
windows主机测试
![vmwareVcenter-windows](https://forum.90sec.com/uploads/default/optimized/2X/7/7271f9719369cdac95e1706a31eb402443cee3df_2_1380x868.png)<br/>

通达oA一键getshell实战测试注意由于网站数量少所以采用自定义线程数来跑如果采用默认线程那么结果不准确

![tongda](https://github.com/Anonymous-ghost/AttackWebFrameworkTools/blob/main/tongda.png)<br/>
druid测试批量测试
![druid](https://forum.90sec.com/uploads/default/optimized/2X/a/aa2297c6a09ba219d4d2451b912fc6251e29ae44_2_1380x698.jpeg) 
ApacheFlink实战png
![Apach](https://forum.90sec.com/uploads/default/original/2X/8/85dafde5a3c59063e5877447361d461c47233682.png) 
ActiveMQ测试
![ActiveMQ](https://github.com/Anonymous-ghost/AttackWebFrameworkTools/blob/main/ActiveMQ.png)
solr动图测试
![gif](https://github.com/Anonymous-ghost/AttackWebFrameworkTools/blob/main/Solr.gif?raw=true)
solr新增exp测试图
![2017](https://github.com/Anonymous-ghost/AttackWebFrameworkTools/blob/main/solr2017.png)
测试结果
![reslut](https://github.com/Anonymous-ghost/AttackWebFrameworkTools/blob/main/result.png)
同类软件Unomi测试对比:某软件测试结果速度有点慢可能是线程开的小
![unomi](https://github.com/Anonymous-ghost/AttackWebFrameworkTools/blob/main/UnoM.png)
我们的软件测试结果和速度几分钟搞定
![myunomi](https://github.com/Anonymous-ghost/AttackWebFrameworkTools/blob/main/UnomiMysoft.png)


另外扯点儿别的话题还开发了针对cms进行测试的工具。这款工具等时机成熟会放出来的暂时不放

![menu](https://forum.90sec.com/uploads/default/optimized/2X/b/b04f08fd772ede5e45145b8cf6df3e2c3067acd9_2_1248x1000.png)
收集漏洞
![menu](https://forum.90sec.com/uploads/default/optimized/2X/6/6ea0808a2eebfc7ec8c4b6aac0c4ae8e47bd4759_2_1246x998.jpeg)
测试
![menu](https://forum.90sec.com/uploads/default/optimized/2X/b/b545a978dccb5c41fa1417f2ae0ac5806652e62f_2_1326x1000.jpeg)

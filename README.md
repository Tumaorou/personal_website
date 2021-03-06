# 文传用户研究中心网站文档
## 站长 许烨臻
## 网站链接 https://reganmian.me/
------
## 一、策划
### 产品文档丶思维导图与网站地图
* __[产品文档](https://github.com/Tumaorou/personal_website/blob/master/file/%E7%BD%91%E7%AB%99%E7%AD%96%E5%88%92%E6%96%87%E6%A1%A3.md)__
* 思维导图

	<img src="https://raw.githubusercontent.com/Tumaorou/personal_website/master/picture/思维导图.png" alt="思维导图" width="40%" height="40%">
	
* 网站地图 https://reganmian.me/sitemap.xml

## 二、管理
### 1、Wordpress信息管理
* __文章vs页面__ 
  * 14篇文章 3个页面
* __标签与分类__
  * 8个分类目录，17个标签。每篇文章至少包含在一个分类目录下并拥有一个标签。分类参考了用户研究的类别和一些实际操作的案例，标签亦是如此。
### 2、Wordpress界面设计
* __选单与侧边栏__
  * 主页菜单分为5个一级菜单，部分菜单下拥有二级菜单，二级菜单个数不超过7个。主页菜单经过多次修改，参考了网上优秀的个人网站及教学网站，最终定下。
* __主页互动性__
  * 主页有搜索框，可进行网站留言，所有文章皆可评论。页面下方可进行登录操作。
* __小工具__
  * `Site Origin`。首页使用`Site Origin`布局

	<img src="https://raw.githubusercontent.com/Tumaorou/personal_website/master/picture/SiteOrigin%E5%B1%95%E7%A4%BA.gif" alt="SiteOrigin展示" width="50%" height="50%">
  
### 3、Wordpress平面设计
* __图库与配色__
  * __[图片版权表格](https://github.com/Tumaorou/personal_website/blob/master/file/%E5%9B%BE%E7%89%87%E6%9D%A5%E6%BA%90.md)__。网站中出现的图片来源分两类，一是出自转载的网络文章，这一类图片均已在所属文章底部标识来源。二是来源于网站*pixabay*有CC0标识的图片。本网站从建设初就严格把控图片来源，需要署名的均已署名。
  * 网站配色采用简朴偏严肃的风格，网站配色在色轮上采取相近颜色，目的是于网站研究的主题契合。做过用户访谈得出的结果。
* __字型丶字体大小与排版__
  * 字型标题h?统一采用微软雅黑（非衬线体），正文p采用宋体（衬线体）。标题字号大于正文，面包屑导航最后一栏略微放大加粗。排版上加粗，换行等参考网上的文章排版。

## 三、运营
### 1、云端架站
* __安全及SSL__
	* 已安装`Wordfence`插件，通过此插件了解自己密码不安全并修改过。已进行**ssl加密**[ssl证书截图](https://raw.githubusercontent.com/Tumaorou/personal_website/master/picture/ssl证书.PNG)
* __多站点__
	* 已开启**多站点**，https://reganmian.me/site2/
* __效能及Availability__
	* 在效能测试网站http://ping.chinaz.com/ 进行测试，共在全世界测试149个节点，因为服务器架在国外，所以国内的ping值普遍比国外低

	<img src="https://raw.githubusercontent.com/Tumaorou/personal_website/master/picture/ping%E5%80%BC.png" alt="ping值测试部分结果" width="50%" height="50%">

### 2、用研
* __[用户访谈](https://github.com/Tumaorou/personal_website/blob/master/file/%E7%94%A8%E6%88%B7%E8%AE%BF%E8%B0%88.md)__
* __[焦点小组](https://github.com/Tumaorou/personal_website/blob/master/file/%E7%84%A6%E7%82%B9%E5%B0%8F%E7%BB%84.md)__
* 结合两项用户研究，通过用户访谈2位新闻学专业同学，本网站将主题由“Best Food”改为“Pacify”，将搜索框放入侧边栏。通过焦点小组结合另外3位站长的建议，网站增加了面包屑导航，将行间距调整至合适宽度等。总体加强了网站的可读性。
### 3、站长工具
* __百度站长工具__，从6月20日提交站点。进行提交关键词，提交链接等，为了使搜索引擎排名靠前，特意将网站大标题加上"文传"两字，使搜索引擎更容易找到。在百度搜索“文传用户研究中心”结果中排行第一

	<img src="https://raw.githubusercontent.com/Tumaorou/personal_website/master/picture/%E7%99%BE%E5%BA%A6%E6%B5%81%E9%87%8F.PNG" alt="百度流量" width="40%" height="40%"><img src="https://raw.githubusercontent.com/Tumaorou/personal_website/master/picture/%E7%99%BE%E5%BA%A6%E6%90%9C%E7%B4%A2%E8%AF%8D%E6%9D%A1.PNG" alt="百度搜索" width="50%" height="50%" align="right">

* __必应站长工具__，从6月25日提交站点。进行提交关键词，提交链接等，在必应搜索“文传用户研究中心”结果中前四均是本网站

	<img src="https://raw.githubusercontent.com/Tumaorou/personal_website/master/picture/%E5%BF%85%E5%BA%94%E7%AB%99%E9%95%BF%E5%B7%A5%E5%85%B7.PNG" alt="必应流量" width="40%" height="40%"><img src="https://raw.githubusercontent.com/Tumaorou/personal_website/master/picture/%E5%BF%85%E5%BA%94%E6%90%9C%E7%B4%A2%E8%AF%8D%E6%9D%A1.PNG" alt="必应搜索" width="50%" height="50%">

* __SEO__，已装`Jetpack`，`Yoast SEO`插件并使用，根据SEO改进提示，给文章均增加关键词。排除SEO问题。

	<img src="https://raw.githubusercontent.com/Tumaorou/personal_website/master/picture/SEO%E9%97%AE%E9%A2%98.png" alt="SEO问题" width="40%" height="40%"><img src="https://raw.githubusercontent.com/Tumaorou/personal_website/master/picture/Jetpack%E7%BB%9F%E8%AE%A1.PNG" alt="Jepack流量" width="50%" height="50%">

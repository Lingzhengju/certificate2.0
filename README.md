   
项目名称
-----
```
证道的光-照亮你的考证道路
```
项目介绍
-----
```
证道的光小程序为一切有考证需求的学生设计，集搜索、匹配、认证、计划一体，
根据学生自身需求、专业背景、职业规划、综测评分规则等要素，向用户提供考证的建议和帮助信息。
能够有效应对就业市场信息不对称、高校教育从精英教育转变为大众教育、
学历含金少而有证含金大，多一证多一路等社会现状。
```
本项目的开发技术包括HTML5、JavaScript、Node.js、MongoDB等，可以通过腾讯云进行部署，
能够通过Web和JS接口调用腾讯开放平台的API，
包括腾讯AI开放平台、腾讯地图开放平台、微信开放平台。
本项目基于腾讯云平台和云南大学智慧教学APP平台，性能可靠，平台稳定性经过长期运行验证。
能够通过腾讯云部署，与腾讯云无缝对接，基于腾讯云部署的成本优势明显，
可以根据访问流量灵活购买腾讯AI开放平台流量套餐，能够精准有效控制开发和运营成本，降低项目风险。
本项目的产品设计坚持KISS设计思想，流程逻辑清晰，易于用户上手使用，UI美观精致，设计规范，
融合了iOS Design、Material Design、WeUI等主流设计风格，符合国内用户使用习惯。
本项目的产品商业模式可行性强，营销内容适度。项目文档和资料规范，编码全部经过语法格式化，
开源文件结构完全符合开源规范。  

部署教程
----
```  
需要修改的参数：
1、环境变量env：云开发控制平台的环境ID
2，asscee_token：Api调用参数
```
```
云数据库的需要上传的文件：
1、swiper-images集合
该集合中需要上传首页需要滚动播放的照片。
2、my_ZS集合
该集合需要提前创建，
由用户在使用过程中对集合进行增、删、改、查用户自己所获得的证书。  
3、pipeiZS集合
该集合中需要上传大量专业名称以及该专业所需要的证书名称。
```
涉及到的外部服务：
1、调用了腾讯开放平台的api进行证书的识别。
2、使用其他考试官网的网址，来进行信息的收集和处理。
3,调用了微信OCR识别API:https://developers.weixin.qq.com/community/servicemarket/detail/000ce4cec24ca026d37900ed551415

项目效果
----- 
<img src="https://https://github.com/Lingzhengju/certificate/blob/test2/QQ%E5%9B%BE%E7%89%8720201113204859.png" width="200" height="400" /><br/>
<img src="https://github.com/Lingzhengju/certificate/blob/test2/QQ%E5%9B%BE%E7%89%8720201113204848.png" width="200" height="400" /><br/>
<img src="https://github.com/Lingzhengju/certificate/blob/test2/QQ%E5%9B%BE%E7%89%8720201113204910.png" width="200" height="400"/><br/>
<img src="https://github.com/Lingzhengju/certificate/blob/test2/QQ%E5%9B%BE%E7%89%8720201113204917.png" width="200" height="400"/><br/>
<img src="https://github.com/Lingzhengju/certificate/blob/test2/QQ%E5%9B%BE%E7%89%8720201113204924.png" width="200" height="400"/><br/>
<img src="https://github.com/Lingzhengju/certificate/blob/test2/QQ%E5%9B%BE%E7%89%8720201113204930.png" width="200" height="400"/><br/>
<img src="https://github.com/Lingzhengju/certificate/blob/test2/QQ%E5%9B%BE%E7%89%8720201113204942.png" width="200" height="400"/><br/>


开源许可证
------
本项目使用GPL v3.license开源许可证，满足开源规范。



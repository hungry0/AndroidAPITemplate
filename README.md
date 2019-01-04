# AndroidAPITemplate
这是一个老外的网站：http://isaratech.com ，提供的一个虚幻安卓原生开发的模板，里面有一些报错，做了一些调整放到了这里，简单的实现了调用一个Toast的接口。  

### 使用方式
在Content同级创建Plugins并将AndroidAPITemplate文件夹完整拷贝进去，右键重新生成项目（可能因为版本不一样出现问题）  

### 之后需要做什么
创建一个蓝图调用Show Toast方法即可。  

### 遇到的问题
Detected problems with API compatibility(visit g.co/dev/appcompat for more info). 打正式包之后这个问题就解决了，需要配置keystore，不过这又是另一个问题了
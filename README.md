# nodebb-plugin-google-analytics-multiple
说明:一个可以配置多个统计的插件。

目前支持两个GA

>参考nodebb-plugin-google-analytics编写。

**安装**

在nodebb package.json中dependencies中手动添加插件地址
```
"nodebb-plugin-multiple-analytics" : "https://github.com/atinosun/nodebb-plugin-multiple-analytics.git"
```
安装使用如下命令:
```
npm install
或者
npm install nodebb-plugin-google-analytics-multiple
```
卸载该插件:
```
npm unistall nodebb-plugin-google-analytics-multiple
```
如遇问题，可以暂时先停掉该插件:
```
在网站根目录下执行
./nodebb reset -p nodebb-plugin-google-analytics-multiple
```

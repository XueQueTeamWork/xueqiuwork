# xueqiuwork

作业描述：

“数据标注”软件需求描述
在对雪球网股票评论进行大数据分析时，需要开发一款辅助软件。这款软件有以下功能：
1.下载某一只/几只股票下的所有评论，如，https://xueqiu.com/S/SZ002353。注意该网站有反爬虫机制。为避免数据被反复下载，数据能够导入导出，断点续传之类。
2.可以自定义一些分类属性，比如评论是否和该股票相关（是/否） 评论正面还是负面还是中性 是否推广贴等
3.针对上面定义的分类属性，用户可以在软件里对每条评论数据的属性加以选择（贴标签）。
4.程序应该能统计用户对评论分类后的分类结果，并以饼图的方式显示。

小组每位成员在github上设立账号，创建一个项目并加入，并且测试github 2个成员同时更新同一文件，然后再合并时导致冲突时，如何解决冲突？每位成员在自己机器上安装tortoisegit 并且起码掌握从github上更新项目。以后上课演示时，不需要大家带u盘，只需要用git同步源代码即可（一开始可能做不到，可以U盘带几次）。

 小组对配置管理的确定（如何管理软件的版本分支，以及软件目录结构的初步设想），小组对编码规范的确定。
 小组项目管理软件/网站的选择及每位成员建立账号。

---------
- [√] 选用语言：Java ，python
- [√] 选用工具：IDEA
- [√] 编码规范： Alibaba Java Coding

----------




------------

流程图：

![image](https://user-images.githubusercontent.com/51170034/111061125-b3d9d080-84dc-11eb-9db1-f76bcae7a4e7.png)


----------


分工：
- [ x] 基础框架
- [ x] 爬虫
- [ x] ui布局设计
- [ x] 数据展示(列表饼图)
- [ x] ppt
- [ x] 测试

-------------
问题：

（1）merge冲突解决：


1、git merge冲突了，根据提示找到冲突的文件，解决冲突
如果文件有冲突，那么会有类似的标记
自己修改标记即可。

2、修改完之后，执行git add 冲突文件名

3、git commit
注意:没有-m选项
进去类似于vim的操作界面，把conflict相关的行删除掉

4、直接push就可以了，因为刚刚已经执行过相关merge操作了



![image](https://user-images.githubusercontent.com/51170034/111254931-1522b080-8651-11eb-88b8-b5146e5e5ba8.png)
![image](https://user-images.githubusercontent.com/51170034/111254956-1d7aeb80-8651-11eb-88c3-a5b0e273698e.png)

------------------



进度
- [ √] 
3.16
首页：


![image](https://user-images.githubusercontent.com/51170034/111258695-739f5d00-8658-11eb-80b0-7fe945dbf24f.png)




- [√]
验证输入的股票id是否正确：
![image](https://user-images.githubusercontent.com/51170034/111495842-b78a8300-877a-11eb-92d5-428deb168472.png)

符合查询资格才能开始爬取数据。



- [ ] 列表 展示 
list：
![image](https://user-images.githubusercontent.com/51170034/111497827-63809e00-877c-11eb-8684-2e080b1f5fd3.png)



添加点击事件，询问是否加入自定义标签。



- [ test] 

菜单栏

- [ test] 

饼图


- [ test]

增删改查

- [ test] 

标签

- [ test]

爬虫

- [ test]

导入数据



code review

- [ x] 


测试

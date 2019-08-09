# 基于CTMediator组件化
## 流程
**我在github上新开了一个组织（organization），在组织内上传我的各个组件。**
### 一  准备工作
**1.1、**创建一个 `MainProject`
![img](https://raw.githubusercontent.com/simplecomponent/Files/master/images/documentImg/ios/%E7%BB%84%E4%BB%B6%E5%8C%96/jietu1.png)
`pod repo add [私有Pod源仓库名字] [私有Pod源的repo地址]`添加源仓库（可以在`/user/.cocoapods/repos`文件夹下找到源工程）
**1.2 、**在`MainProject`同级`clone`脚本:`git clone git@github.com:casatwy/ConfigPrivatePod.git`
**1.2、**将`ConfigPrivatePod的template文件夹下Podfile中source ‘https://github.com/ModulizationDemo/PrivatePods.git'`改成前面你自己的私有Pod源仓库的repo地址
**1.3、**将`ConfigPrivatePod`的`template`文件夹下`upload.sh`中`PrivatePods`改成前面你自己的私有Pod源仓库的名字







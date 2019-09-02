---
layout: post
title:  "Mac 将 App 程序打包成为 dmg"
date:   2019-08-23 08:32:36 +0800
author: "MLeo"
categories: app dmg swift mac

---

# App to DMG 打包流程  

### 1. 新建DMG  
**打开磁盘工具，新建DMG**  
```bash
File->New Image->Blank Image
```
![15665433118042444](http://images.ichochy.com/15665433118042444.png)  

**创建DMG**
![15665435757953755](http://images.ichochy.com/15665435757953755.png)  

### 2. 添加文件  
**`在磁盘工上右键打开`**  
```bash
右键->Show in Finder
```
![15665436347971226](http://images.ichochy.com/15665436347971226.png)  

**创建快捷键**  
```bash
ln -s /Applications Applications
```
**完成文件添加**   
![15665449057641887](http://images.ichochy.com/15665449057641887.png)  

### 3. 排版，添加背景  
**修改排版**  
```bash
右键->Show View Options
```
![156654596473115412](http://images.ichochy.com/156654596473115412.png)

**自定义背景**  
![15665451417533438](http://images.ichochy.com/15665451417533438.png)  

### 4. 压缩DMG  

**推出DMG**  
![15665454417422579](http://images.ichochy.com/15665454417422579.png)

**转换DMG**  
![156654547374332110](http://images.ichochy.com/156654547374332110.png)

**压缩DMG**  
![156654560673824711](http://images.ichochy.com/156654560673824711.png)  
**压缩后的文件明显小于原文件，也不可再进行编辑**


### 5. 完成打包  
**至此，完成了App打包DMG，可以进行共享发布了**



---
### 联系方系：  
> 邮箱：[iChochy@qq.com](mailto:iChochy@qq.com)   
> 网站：[http://www.ichochy.com](http://www.ichochy.com)  
> GitHub： [https://github.com/iChochy]( https://github.com/iChochy)   

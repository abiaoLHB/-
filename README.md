# web前端开发规范
## 一、css部分
## [参考链接](http://nec.netease.com/standard/css-sort.html)
## [百度规范]（https://github.com/fex-team/styleguide/blob/master/css.md）
### （0）注意事项
- 1、一律小写
- 2、尽量用英文
- 3、尽量不加 `-` 中划线
- 4、尽量不缩写，除非一看就明白的单词
- 5、避免使用标签选择器
- 6、避免使用单个属性选择器
- 7、不要在 `ID` 选择器前使用标签名
- 8、选择器最好不要超过三层
### （1）css类名命名规范
* 头部 header
* 尾部 footer
* 导航 nav
* 子导航 subnav
* 侧栏 sidebar
* 内容 content/container  
* 栏目 column
* 外围容器 wrapper
* 左右中 left right center
* 登录 loginbar
* 下载 download
* 菜单 menu
* 子菜单 submenu
* 搜索 search
* 友情链接 friendlink
* 版权 copyrigh
* 滚动 scroll
* 标签页 tab
* 列表 list
* 提示信息 msg
* 标题 title
* 指南 guild
* 服务 service
* 注册 regsiter
* 状态 status
* 合作伙伴 partner
* 投票 vote
### （2）id名命名规范
* 容器: container  
* 页头：header  
* 内容：content/container
* 页面主体：main  
* 页尾：footer  
* 导航：nav
* 侧栏：sidebar  
* 栏目：column  
* 页面外围控制整体布局宽度：wrapper
* 左右中：left right center
* 主导航：mainbav  
* 子导航：subnav
* 顶导航：topnav  
* 边导航：sidebar  
* 左导航：leftsidebar
* 右导航：rightsidebar  
* 菜单：menu  
* 子菜单：submenu
* 标题: title  
* 摘要: summary
* 标志：logo  
* 广告：banner  
* 登陆：login  
* 登录条：loginbar
* 注册：regsiter  
* 搜索：search  
* 功能区：shop
* 标题：title  
* 加入：joinus  
* 状态：status  
* 按钮：btn
* 滚动：scroll  
* 标签页：tab  
* 列表：list  
* 提示信息：msg
* 当前的: current  
* 小技巧：tips  
* 图标: icon  
* 注释：note
* 指南：guild 
* 服务：service  
* 热点：hot  
* 新闻：news
* 下载：download  
* 投票：vote  
* 合作伙伴：partner
* 友情链接：link  
* 版权：copyright
### （3）颜色命名规范
```css
.red { color: red; }
.f60 { color: #f60; }
.ff8600 { color: #ff8600; }
```
### （3）字号命名规范
```
.font12px { font-size: 12px; }
.font9pt {font-size: 9pt; }
```
### （4）对其样式命名规范
```
.fl { float:left; }
.fr { float:right; }
.fb { float:bottom; }
```
### （5）去掉小数点前的“0”
```js
font-size: .8rem 
```
### （6）推荐中划线 `-` 连接样式名，不推荐使用下划线 `_`
```js
main-title{
    color:red;
}
```
### （7）不要随意使用Id
```js
id在JS是唯一的，不能多次使用，而使用class类选择器却可以重复使用，另外id的优先级优先与class，所以id应该按需使用，而不能滥用。
```

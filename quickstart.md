## 区块

区块用于关联链接，显示自定义排序数据，比如：导航条、推荐排行、热门列表。

在后台区块菜单进行编辑，默认有添加几个常用的区块类别。

>    前台通过 \service\Block::shows 方法调用。
>
>    阅读 app_frontend/themes/default/site/index.php 获得范例。

## 根目录 /service

这个目录下的文件用于辅助model类，一般用于缓存model。

## 根目录 /wskm

这个目录下的文件用于扩展yii类、封装第三方类等辅助作用。如果yii已有的类无法帮助你，你可以在此目录中寻找帮助。

## 缓存更新

如果你使用的 \service\Block 和 \service\Content 类获得的缓存数据，可通过后台设置中的“刷新缓存”配置项来立即更新缓存。

# SDCellAutoHeight
使用SDAutoLayout（Github地址：https://github.com/gsdios/SDAutoLayout ）自动布局和cell高度自适应功能制作的demo！
自动布局和cell高度自适应视频教程：http://www.letv.com/ptv/vplay/24038772.html

自动布局示例：

/* 用法一 */
_view.sd_layout

.leftSpaceToView(self.view, 10)

.topSpaceToView(self.view, 80)

.heightIs(130)

.widthRatioToView(self.view, 0.4); 


/* 用法二 （一行代码搞定，其实用法一也是一行代码） */
_view.sd_layout.leftSpaceToView(self.view, 10).topSpaceToView(self.view,80).heightIs(130).widthRatioToView(self.view, 0.4);

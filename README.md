# imgFullView

让图片随手机倾斜改变位置的插件。

**适用场景：**当手机竖屏状态展示16:9尺寸的图片时（图片长大于宽），若要展示完全，则上下空间就被浪费，而且图片缩小，体验不好。

使用该插件可以使图片高度为屏幕的100%，当左右倾斜手机时，图片会随着手机的倾斜角度而移动，方便显示较宽的图片。

**用法：**
`var fullView = new ImgFullView('selector'); //初始化插件，'selector'为目标图片外包裹容器的选择器，如：`

`<div class="box">`
`    <img src=".." alt="..">`
`</div>`

`var fullView = new ImgFullView('.box');`

`fullView.setCurrentIndex(index); //当有多个图片时，可以指定某个图片为活动状态`

项目中用到的功能，写的还不是很完善，先挖个坑，以后如果有空再填
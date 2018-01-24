> 使用方法

```javascript
  // sw_container pageation 传递的 均是一个 class 类名
new LeSwiper("sw_container",{
	loop:true, //可选项 如果未设置，在滑动的时候如果碰到边界则会反弹
	autoplay:3000, //可选项 默认不会执行自动播放
	pageation:"pageation" //可选项 如果不需要 pagination 可以不设置，如果设置了不想要原来的css 样式，可以添加css样式覆盖
})
```

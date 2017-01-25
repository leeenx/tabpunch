# tabpunch 简介

一个实现 tab 小三角打孔的 sass 方法。依赖 (sass-svg)[https://github.com/leeenx/sass-svg] 库。

## tabpunch 用法

```scss
	// 默认调用
	@include punch;
	// 自定义小角的宽高
	@include punch(10, 10);
	// 使用 rem 单位，并且 rootFontSize = 20px
	@include punch(rem(10), rem(10));
	// 使用 rem 单位，并且 rootFontSize = 100px
	@include punch(rem(10), rem(10), 100);
	// 定义 tab 的极限宽高为 750px 和 400px
	@include punch(rem(10), rem(10), null, 750, 400);
```

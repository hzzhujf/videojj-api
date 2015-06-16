# videojj-api

### USAGE
```js
<link rel="stylesheet" type="text/css" href="Iva.css">
<script type="text/javascript" src="Iva.js"></script>
/**
 * 创建Iva实例
 */
var ivaInstance = new Iva('父容器id',// 父容器id，为了保证浏览体验，请给父容器设置宽高860px*480px以上
	{
		video: '视频播放地址',// http://v.youku.com/v_show/id_XODIzNTE5NTY0.html
		cover: '视频封面，可选 '// 视频封面，可选
	}
);

/**
 * 销毁Iva实例
 */
ivaInstance.destroy();
```

### [FAQ](http://doc.videojj.com)


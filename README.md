### row_nav 使用说明

> 引入组件：

```
import rowNav from '@/components/common/advertisement/row-nav.vue';

export default {
	components:{
		rowNav
	},
}
```

> 使用组件

```
<row-nav :resdata="rownavs" />
this.rownavs = [{ src: '/static/images/index/diaocha_btn2.png', text: '' }, { src: '/static/images/index/diaocha_btn.png', text: '' }];

### 使用说明

row_nav 组件使用说明
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
```

cardNav 组件使用说明
> 引入组件：

```
import cardNav from '@/components/common/advertisement/card-nav.vue';

export default {
	components:{
		cardNav
	},
}
```

> 使用组件

```
<cardNav :resbannerdata="resbannerdatas" />
this.resbannerdatas = [
		{ src: '/static/images/main_shop/shop_1.png', title: '', subtitle: '', my: '0upx' },
		{ src: '/static/images/main_shop/shop_2.png', title: '', subtitle: '', my: '0upx' },
		{ src: '/static/images/main_shop/shop_3.png', title: '', subtitle: '', my: '1%' },
		{ src: '/static/images/main_shop/shop_4.png', title: '', subtitle: '', my: '1%' }
	];
```

combination-nav 组件使用说明
> 引入组件：

```
import combinationNav from '@/components/common/advertisement/combination-nav.vue';

export default {
	components:{
		combinationNav
	},
}
```

> 使用组件

```
<combinationNav :resdata="combinationnavs" />
this.combinationnavs = [
		{
			titlesrc:'/static/images/main_shop/shop_10.png',
			src: '/static/images/main_shop/shop_12.png',
			title: '',
			subtitle: '',
			my: '10upx',
			subdata: [
				{ src: '/static/images/main_shop/shop_13.png', title: '', subtitle: '', my: '5upx' },
				{ src: '/static/images/main_shop/shop_14.png', title: '', subtitle: '', my: '0upx' }
			],
			bottomdata:[
				{ src: '/static/images/main_shop/shop_15.png', title: '', subtitle: '', my: '5upx' },
				{ src: '/static/images/main_shop/shop_16.png', title: '', subtitle: '', my: '0upx' },
				{ src: '/static/images/main_shop/shop_17.png', title: '', subtitle: '', my: '5upx' }
			]
		}
	]
```
five-nav 组件使用说明
> 引入组件：

```
import fiveNav from '@/components/common/advertisement/five-nav.vue';

export default {
	components:{
		fiveNav
	},
}
```

> 使用组件

```
<fiveNav :resdata="fivenavs" />
this.fivenavs = [
		{
			src: '/static/images/main_shop/shop_5.png',
			title: '',
			subtitle: '',
			my: '0upx',
			subdata: [
				{ src: '/static/images/main_shop/shop_6.png', title: '', subtitle: '', my: '0upx' },
				{ src: '/static/images/main_shop/shop_7.png', title: '', subtitle: '', my: '0upx' },
				{ src: '/static/images/main_shop/shop_8.png', title: '', subtitle: '', my: '2%' },
				{ src: '/static/images/main_shop/shop_9.png', title: '', subtitle: '', my: '2%' },
			]
		}
];
```

fore-nav 组件使用说明
> 引入组件：

```
import foreNav from '@/components/common/advertisement/fore-nav.vue';

export default {
	components:{
		foreNav
	},
}
```

> 使用组件

```
<fore-nav :resdata="forenavs" />
this.forenavs = [
		{ src: '/static/images/index/index_zhuanjia.png', title: '问专家', subtitle: '制定专家作答' },
		{ src: '/static/images/index/index_shexiang.jpg', title: '快速提问', subtitle: '传图提问' },
		{ src: '/static/images/index/index_jifen.png', title: '积分商场', subtitle: '信息员兑换商品' },
		{ src: '/static/images/index/index_nongji.jpg', title: '农机服务', subtitle: '专业 迅捷 安心' }
];
```

## ��װ

```
npm install m-select 
```

## ʹ��

```
import MSelect from 'm-select'

var ms = new MSelect({
	options: cityData,
	level: 2,
	renderTo: "#selectCtn",
	selectedIndex: [1, 2],
	change: function (data) {
	
	},
	complete: function (data) {
	
	}
})

ms.show()
ms.hide()
ms.reset()
```
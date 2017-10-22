---
layout:     post
title:      "安卓代码段--跳转activity通过intent穿参数"
date:       2017-10-21 00:00:00
author:     "shaomiao"
header-img: "img/post-bg-android.jpg"
tags:
    - Android
---
putExtra传递参数
		intent.putExtra("data","hello word");
		startActivity(intent);
	}
});

-------------------------------------------

Intent i=getIntent();
//通过getStringExtra接收string类型参数
String data= i.getStringExtra("data");

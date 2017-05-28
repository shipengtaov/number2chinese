数字转为汉字
===========

只能转 `0<= x < pow(10, 12)` 之间的整型数字

#### 使用

	>>> number2chinese(0)
	零

	>>> number2chinese(10)
	十
	
	>>> number2chinese(17)
	十七

	>>> number2chinese(1000)
	一千
	
	>>> number2chinese(1002)
	一千零二
	
	>>> number2chinese(10100)
	一万零一百

#### unittest:

	pytest


### License

MIT

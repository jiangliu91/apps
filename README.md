# apps
1.科大讯飞智慧课堂平板之前大多是联想系或者荣耀系低端机，此类平板基本都可以解除bl锁，进行刷机操作，这里就不在赘述；在2019之后采用的基本是华为c系列面向企业的定制机，此类在fastboot下无解锁码的情况下无法一般线刷，可以使用猎人刷机工具或者华为官方工具（需拆机短接），进行强刷（无法找到刷机包或者刷机工具自行寻找淘宝解决）。 2.刷完之后选择性恢复官方软件，可以实现即用科大讯飞智慧课堂功能（离线登陆除外，须科大讯飞管控套件，但是装上后会背锁机，启动器也是），且用户登录无法常驻，使用时需手动登录。 3.科大讯飞的软件商店需要有管控平台的存在，因此必要更新软件是需要打开adb调试装上所有套件，更新后adb提取（部分可以在设置中恢复原来桌面并删除管控平台来达到同样效果，且管控平台只能隐藏设置中的内容，无法删除）。 4.科大讯飞后台检测用户登录情况，用户登录在没有必要套件情况下无法常驻，因此还有一种解决办法。管控平台检测软件时是以包名为依据，因此可以修改包名后恢复官方启动器并装上管控平台，来达到隐藏效果。 5.科大讯飞用户登录会检测mac地址，因此一个账号只能绑定一个平板，但是如果其他平板或手机修改mac，也能等陆。

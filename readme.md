# 说明

原先没有整理工程的时候编译的可执行文件路径: `./main`
编写makefile文件后生成的可执行文件路径: `./bin/vending.exe`

`product.json` 是储存商品的信息; 程序执行完成之后不会吧商品信息重新写入文件;可以认为只读文件

`img` 是所有需要展示的图片,包括主页,购物车页面, 支付页面
    其中关于商品的图片名称应该`product.json`中的"name"保持一致


`simfang.ttf` 是字库文件

项目是部署在arm架构的开发板上的;需要移植其他架构,需要重写设备文件的类, 路径在: `cls_lcd`, `cls_tou`

# 注意事项


# 移植说明

    


# 作者


# 修改时间 和 版本
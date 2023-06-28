# proctol-convert
usb转i2c、spi、uart、pwm、gpio、swd、adc  
基于RP2040制作  
>设计之初是为了平替85多的Debug probe  
>最低成本约80元(自己制作钢网的话)  
## PCB制造注意事项  
pcb用嘉立创eda画的，修改导入dxf而不是ad的文件  
bom表中不含rp2040和W25Q16JVUXIQ(rp2040的flash)  
推荐使用[立创商城](http://szlcsc.com "立创商城")购买，bom可全部匹配  
同时可以把pcb打了再贴片  
## 用[嘉立创](http://jlc.com "嘉立创")的制作成本  
(元器件价格约80元(不含运费))
下表中价格不含元器件，不含手工成本

| 使用的功能  | 组合0 | 组合1 |
| ------------- | --- | --- |
| SMT贴片(2件,全贴) | 是 | 否 |
| 开激光钢网 | 否 | 是 |
| 价格(RMB) | 400(含元器件) | 100 | 

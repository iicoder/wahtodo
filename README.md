# what are we going to do


- 想做一个python QRCODE 的识别包

  给出一张图片，只要里面有可识别的二维码，就给出坐标范围和解码内容
  
  同时也可以提供生成二维码的图片，插入图片的某个位置
  
- jsondb（bsondb）[org](https://github.com/bsondb)地址
  
  对标SQLite, Mongo，no-sever 要有锁和索引
  
  集成bson、btree等,支持内存管理，page划分对应到disk
  
  模仿mongodb API，至少curd吧，未来有json的聚合，导入导出
  
  
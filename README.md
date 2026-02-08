## 前言

欢迎来到外卖商城平台的微信小程序+SSM项目！本项目旨在为用户提供便捷的外卖服务，结合微信小程序的广泛覆盖和SSM框架的强大功能，打造一个高性能、易用性的外卖商城平台。

## 内容介绍

本项目包括以下功能模块：商品展示、分类浏览、购物车、订单管理、用户管理等。通过这些模块，用户可以轻松浏览各种美食，挑选心仪的商品，实现一站式购物体验。同时，后台管理端为商家提供便捷的商品管理、订单处理等功能，助力商家高效运营。

## 技术介绍

### 语言：Java
### 使用框架：Spring Springmvc，MyBatis，微信小程序
### 前端技术：JS、Vue、CSS3，Uniapp
### 开发工具：IDEA/Eclipse，Uniapp
### 数据库：MySQL 5.7/8.0
### 数据库管理工具：phpstudy/Navicat
### JDK版本：jdk1.8
### Maven: apache-maven 3.8.1-bin
### 前端环境：Node.Js 12\14\16

## 核心代码

以下为项目中的一个核心代码片段，展示了如何实现商品分类的查询功能：

```java
// 商品分类Service层
public List<Category> getCategoryList() {
    return categoryMapper.selectByExample(new CategoryExample());
}

// 商品分类Mapper层
public interface CategoryMapper {
    @Select("SELECT * FROM category")
    List<Category> selectByExample(CategoryExample example);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/345942/19/3011/141343/68c57300Fc1bdd4bb/1adef1cf22a633a6.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/324482/28/19659/27315/68c572d8Ffeb32311/38d9e9e25b96c772.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/329008/16/19691/62515/68c572d8Fa7cc6311/a8ca0b1388214bc8.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/344870/20/2949/18281/68c572d8F63ce8548/8e48ad46afe2ad6f.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/332133/17/12773/16520/68c572d8Fa29a3afd/90fd8a969dea010a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/339224/40/10429/54975/68c572d8Fd2603d83/c06ec3833bf8953c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/327036/17/19548/8555/68c572d8F1e840888/1b6b608e22575453.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/332882/36/12817/25323/68c572d9F96768df6/eb4b6a50c5ac5190.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336996/14/10542/70732/68c572d9Fb8a4601e/1fabd7395bf59645.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/325096/17/19548/43862/68c572d9Fba857068/3a8654f9aab4ae29.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)

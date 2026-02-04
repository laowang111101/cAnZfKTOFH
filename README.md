## 前言

此项目是基于微信小程序的食堂菜品查询平台，是我为毕业设计所开发的实战项目。整个项目采用Java语言，结合Spring Boot框架，以及前端技术JS、Vue和CSS3等，旨在提供一种便捷的食堂菜品查询方式。以下是对该项目的详细介绍。

## 内容介绍

本项目的主要功能包括食堂菜品的查询、分类浏览、口味筛选等。用户可以通过微信小程序，随时随地查询到食堂的菜品信息，方便快捷。同时，后台管理系统可以方便地管理菜品数据，包括添加、修改和删除菜品信息。此外，项目还提供了用户反馈功能，以便及时了解用户需求，优化食堂服务。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是项目中的一部分核心代码，展示了如何实现菜品查询功能：

```java
// 获取菜品列表
@RequestMapping(value = "/getDishList", method = RequestMethod.GET)
public List<Dish> getDishList(@RequestParam("categoryId") Integer categoryId,
                              @RequestParam("taste") String taste) {
    Dish dish = new Dish();
    dish.setCategoryId(categoryId);
    dish.setTaste(taste);
    return dishService.getDishList(dish);
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

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/346931/37/717/94014/68bdadf4F99ac95f6/d4b3c2460c34278d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/331881/2/10628/25205/68bdadccF9d8f415f/a94b476215e716e7.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/334612/34/10609/10653/68bdadccF5041c76d/382eee2f93c83a70.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/349073/33/759/21794/68bdadceF56b58e44/fe8e9e96f148b2f7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/334916/17/10500/22867/68bdadceFa536c7bb/c3b037acfcda5751.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/347569/5/796/24028/68bdadcfF52b4bc46/38889dc84ba0fe11.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/345843/31/766/43115/68bdadcfF86deda22/6be733dd4b2979f4.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/328839/6/17461/19526/68bdadd1F88361a30/a2efb7cea0c4e7e8.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/349388/39/778/40070/68bdadd1F736b82dd/72a708e0997711f9.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/297674/20/19328/58673/68bdadd2Fd78e482c/4fcaa97f6f447350.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)

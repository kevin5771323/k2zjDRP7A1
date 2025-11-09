# 前言

随着社会的进步，汽车已经成为人们生活中不可或缺的一部分。为了满足汽车维修管理的需求，我们开发了一款基于Spring Boot的汽车维修管理系统微信小程序。在此，我们愿意将这个项目的源码分享给大家，希望能帮助到有需要的人。

# 内容介绍

本项目是一个集汽车维修管理、员工管理、订单管理等功能于一体的微信小程序。通过使用Spring Boot、Spring MVC、MyBatis等后端技术，以及Vue、Uniapp等前端技术，实现了高效、易用的汽车维修管理系统。用户可以通过微信小程序轻松预约维修、查询订单、管理员工等。

# 技术介绍

## 语言：Java

## 使用框架：
- Spring
- Spring MVC
- MyBatis
- 微信小程序

## 前端技术：
- JS
- Vue
- CSS3
- Uniapp

## 开发工具：
- IDEA/Eclipse
- Uniapp

## 数据库：
- MySQL 5.7/8.0

## 数据库管理工具：
- phpstudy/Navicat

## JDK版本：
- jdk1.8

## Maven：
- apache-maven 3.8.1-bin

## 前端环境：
- Node.Js 12\14\16

# 核心代码

以下是项目中的一段核心代码，展示了如何通过MyBatis实现汽车维修信息的查询：

```java
// CarRepairMapper.java
public interface CarRepairMapper {
    @Select("SELECT * FROM car_repair WHERE id = #{id}")
    CarRepair selectCarRepairById(@Param("id") int id);
}

// CarRepairService.java
@Service
public class CarRepairService {
    @Autowired
    private CarRepairMapper carRepairMapper;

    public CarRepair getCarRepairById(int id) {
        return carRepairMapper.selectCarRepairById(id);
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/333693/25/12903/147580/68c59f7dF2c3432b3/c1f20cc3d88f1412.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/326784/1/19625/47100/68c59f54F0ddcc746/94c5d07ab4b8d158.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/322953/9/15533/62724/68c59f55Fab03277e/d2007f5f5c4d73c0.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/301947/35/17873/24180/68c59f55Ffdb9318d/99cb2f590cbe5544.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/340671/25/9104/13926/68c59f55F994f2c5c/ba5169b105a1e69a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/343918/3/3200/27906/68c59f55F639827f3/97ec3fc0aa49c00a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/325590/35/19663/76508/68c59f55Fda659e27/1bb92f05e0a90221.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/337871/38/10396/91857/68c59f55F7643f7e1/c3e56691760dc742.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/326793/26/19620/16689/68c59f56F4a1cd3ec/1f95f1523c7f04d8.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326251/38/19669/52151/68c59f56F95b7ddd0/d71747cb8bdb9b35.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)

---
title: "Querym, 5 months into open source"
description: "Querym, 5 months into open source. What I've learnt in these 5 months"
pubDate: "Oct 10 2023"
heroImage: "/querymaster-screen1.png"
---

I've had [Querym](https://github.com/querymx/Querym) for five months. It is a cross-platform database client that is open source. We initially solely supported MySQL, but more recently, PostgreSQL support was introduced. There are ups and downs along the journey, and this is what I learn.

## Escape the hell of Windows SmartScreen

I have always thought that Windows would be the easiest platform when it come to packaging and distributing my application. But in reality, it is the most difficult and expensive one.

![Windows SmartScreen](/windows-smartscreen.png)

Windows requires you to sign your application to remove the warning. I bought the IV (Individual) certificate for around $150 per year. To sign your application, you need hardware to sign. Since I don’t have hardware to sign and I need to integrate it to CI/CD pipeline, I need to pay $180 per month for cloud signing.

I thought that it will remove the download warning and I couldn’t been any wrong, the warning was still showing. After some google, even with valid certificate, the warning will persist until you build reputation for your certificate. For Windows to stop complaining, thousand of people need to download and use your app. But this is problematic because we need a lot of people to download the app to remove the warning, but people will not download the app if there is warning. To really bypass it, you need to buy EV certificate. It is even more expensive.

The final solution is to build the app into .appx and submit it to Windows Store. It is a lot of cheaper because I only need to pay $19 one time and there is no warning. But Windows Store is not that popular.

## Marketing your open source

![Windows Store for Querym](/microsoft-store-querym.png)

One of the key driving motivation of open source is to see people using your product. But with million of open source project around the world, you need to fight for spotlight. Here are several approach that I am taking

- **Approach local developer community**. This is at the moment the most effective way. I am lucky that I am community founder of a very active local online developer community. This give me a platform to showcase my work.
- `good-first-issue` **tag works**. By adding some easy issues for people to complete, it will attract people to your project. Github seem to promote your project if there are some `good-first-issue` issues in your project.
- **Microsoft Store**. Surprisingly, there are a few people discover us via the store even our ranking is not relatively high when search. I believe if I optimize the listing information and make it more attractive, it could drive significant users.
- **Other online community** like Discord and Reddit. This is not as effective as I thought but at least it contributes a bit of traffic to the projects.

Marketing is very important because I need more people to use so that I can collect more feedback on how to build valuable projects.

## Early Testers

Getting early testers is the most important thing to move this project forward. I am lucky to have a few developer friends who constantly use it and give feedback.

## Usages

![Querym Screenshot](/querymaster-screen1.png)

Currently, my app has average of 6 users using it per day. At the peak, there are 21 users. The number is very low but it is slowly growing. I believe that it will grow fast once we have sizable user-base as people will help spreading the word if the app is valuable.

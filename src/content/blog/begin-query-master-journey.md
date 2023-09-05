---
title: 'QueryMaster begins - invisal/profile'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Sep 05 2023'
heroImage: '/blog-placeholder-3.jpg'
---

In early 2023, the majority of our developers switched to Mac. Previously, we had been using HeidiSQL as a client, but we couldn't find a similar client for Mac. We tried numerous other clients and weighed their pros and cons.

As a developer who likes to challenge myself, I wondered how difficult it would be to write our own client. So, I started QueryMaster as an open-source project. [QueryMaster](https://github.com/invisal/query-master) aims to replicate the features that we liked from each database client and make it lightweight and cross-platform.

I have committed at least 7-10 hours to developing this client. After 3 months of development, we now have a bare minimum client. However, there is still much to be done.

![QueryMater](/querymaster.png)

## Market Opportunity

There are over 27 million software developers around the world, and the majority of them will touch a database at some point in their career. There are three ways to work with databases: programmatic, command line, and graphical interface. Graphical interfaces provide a convenient way of managing databases and are more beginner-friendly.

While there are many existing clients in the market, I still strongly believe that there is a huge market for this kind of tool:

- There are many new database engines, and it is impossible for any database client to cover them all.
- There are many features, and different developers prefer different ways of doing things. It is hard for one client to satisfy every developer.
- Some features are locked behind a paywall with high prices.

There are some successful startups that are based on database GUI.

- 2023-04-11: [DBeaver takes $6M seed investment to build on growing popularity](https://techcrunch.com/2023/04/11/dbeaver-takes-6m-seed-investment-to-build-on-growing-popularity)
- 2022-02-09: [PopSQL Raises $14M Series A from Tiger Global to Help Data Teams Collaborate](https://popsql.com/blog/series-a)

Hopefully, it can reach Postman potential.

- 2021-08-18: [API platform Postman valued at $5.6 billion in $225 million fundraise](https://techcrunch.com/2021/08/18/api-platform-postman-valued-at-5-6-billion-in-225-million-fundraise/)

## Competitors

There are plenty of database GUI clients available in the market, although this is not an exhaustive list. The majority of these clients are locked behind a paywall, while some offer limited functionality for free users.

| Product	| Free Tier	| Personal (Year) |	Commercial (Year) |
| --- | :---: | ---: | ---: |
| DataGrip | | $99 | $229 |
| Navicat	|	| $350 | $700 |
| dbForge	| |	$110 | $260 |
| SQLPro | | $100 |
| TablePlus |✅ | $89 | $129 |
| Dbeaver |	✅ | $110 | $250
| Beekepper Studio | ✅ | $84 | $132 |
| DbVisualizer |✅ | $197 | $197 |
| Database Client (VSCode Plugin) | ✅ | $20 |
| HeidiSQL | | Free | Free |
| DbGate | | Free | Free |
| Sequel Pro | | Free | Free |
| phpMyAdmin | | Free | Free |

## Conclusion

I have high hopes for this project and am looking forward to releasing it to the market within the next 3 months.
---
layout: post
title:  "Hot v/s Cold Cloud Storage"
author: kaustubh
categories: [ explanation, guide ]
image: assets/thumbnails/hot-cold.png
comments: true
---

Everyone is moving towards cloud storage and maybe cloud computing. When you build an application of web application you want to deploy it somewhere. Now you have two choices:

- You can either buy hardware by yourself and spend on a huge amount of hardware and then you have to configure it deploy the application and then for the entire life you have to manage it.
- On the other hand, you can also go for cloud service where you just have to deploy the application, and then you have to pay for use. You're not doing upfront investment.

Cloud storage is used by not just companies but also individuals or normal consumers. We are using it to store our photos & files example I have all my documents on the cloud storage maybe on Dropbox or Google Drive or maybe some other storage.

Let's say you have the archived data of 5 GB so then at 5 GB data is stored on your cloud service and you're not even using it. So let's say you don't want to use that data for maybe next one year maybe you want to use it tomorrow but so let's say you're not sure how soon you want to access that data and that's we're saving that data on the cloud storage will be positive because you're paying it for monthly use so you have to pay every month and you're not even using that and that's where we have a concept of hot storage and cold storage.


Every company has its own way of defining it. Now for some companies, hot storage simply means that you and your server are connected continuously. That means they are online the moment you ask for data you will get it instantly.
The cold storage for them is offline storage. So, let's say you have your data center somewhere and you don't know where it is and you are storing that data in that data center and that is offline. The moment you say hey I want data from the data center they will say ok you need that data then wait for five hr & we will give it. They will take the drives and they will connect it with this server and then you can access that data and that to the speed will be damn slow.

**Some Points**

- You will not get your data instantly in cold storage. The throughput will also be slow but what's the advantage of using it. Then the advantage is since that connection is not continuous with the server, you don't have to actually pay a huge amount of money to access that and that's where we have to choose between hot storage and cold storage.

- Hot storage is you want to use your data frequently and you want it instantly & on the other hand, the cold story is basically where you can store your data for a longer time and if you want data you may have to wait for three to five hours.

We have two big companies Amazon and Google. Google has their own cloud service and for the cloud storage, if you want hot, they have a different one for the cold one they named it as cold a line. On the other hand, we have AWS (Amazon Web Services) which has one of the best cloud services even they have S3 which is a Simple Storage Service.

This was all about Hot and Cold storage. If are liking my way of writing and want future articles just subscribe to my blog (it's free!) and leave a comment if are still confused about anything and suggest me more topics on which I can write.

Happy Reading Folks!
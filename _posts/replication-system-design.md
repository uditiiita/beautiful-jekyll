---
layout: post
title: Replication
gh-badge: [star, fork, follow]
tags: [test]
comments: true
categories: SystemDesign Replication SDI
---

## What is Replication?
Replication means storing single piece of data on multiple machines to increase the availability. The whole idea is to keep redundant data so that if one server holding copy of data goes down, then another server holding copy of same data can take over and handle the requests.  
When doing replicatio, we assume that the whole server is able to handle the complete data. We do not need to partition the data. When a single server is not able to partition the data, then it becomes the problem of partitioning which is out of scope of this tutorial and  needs a full tutorial in itself.

## Why is it needed?
The main goal of replication is to increase the availability of the system you are building. If there is only single server storing your data and if that server goes down, then your system becomes unavailable right? To solve this problem, you keep multiple servers for same data so that if one  goes down, another can still handle the requests.

## When is it needed?
If you have immutable data i.e., data which never changes, then you can just put multiple copies of data at once and that will solve your purpose.  
But what if you have changes happening to your data every now and then. In such cases, you cannot copy data manually to multiple machines. You need to put in some mechanisms to handle copying of data from one server to another in real time. This is the real problem which is actually solved by replication.

## Whats the biggest challenge in Replication?
Biggest challenge of replication is consistency. Since you are now copying data onto multiple servers.  
Let's say there are server A and server B. Request to store data comes on server A. Data gets stored on server A and success response is sent. Now before replication service could have replicated the data to another server, lets say another request to get the previous data came which lands on server B. It is clearly evident that this request will fail now because this data is not copied to server B till now. 

## Why do we use replication then if it breaks consistency?
This whole process of copying data is called eventual consistency. Here your system is not fully consistent as we just saw. However, the benefit you are getting is really big. Your system has become available now. 
Also, if you try to analyze the actual hit that you have to take, then you will realize that it is actually not that much. In eventual consistency, data gets replicated within a second which is fine for almost most of the systems that you build. 
Though, if you still need consistency as well as availability, then still there are some solutions like quorums which will provide you both but then your latencies will increase a bit. 

## How is it done?
TBD
---
title: "Sorting Ordered Data in a Key-Value Store"
url: "https://blog.kvdb.io/2019/11/01/sorting-ordered-data-in-a-key-value-store"
date: "2019-11-01"
author: ""
feed_url: "https://blog.kvdb.io/feed.rss"
---
Most key-value databases, including KVdb, store keys in a lexicographic order. What does this mean? Imagine you save some values to a bucket: Set peach Set apple Set kiwi What order will the keys be returned when enumerating the bucket? apple , kiwi , peach as expected. It’s basically dictionary order. What about numbers? Aha! Good question: Set 10 Set 2 Set 1 How are the keys returned? 1 , 10 ,...

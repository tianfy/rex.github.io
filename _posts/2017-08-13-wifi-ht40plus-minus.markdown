---
layout: post
category: "wireless"
title:  "11naHT40 11naHT40plus 11naHT40minus的意思"
tags: [无线,HT40]
---
### 简介

>802.11na中HT40加减的意思   


### 描述
```
AP中802.11n默认是支持的，不需额外配置。如果radio设为11b，即是802.11ng，如果radio设为11a，即是802.11an。 
11na_ht20代表802.11na的20兆频宽，连接速率有130M，11na_ht40代表802.11na的40兆频宽，连接速率有300M。由于802.11n有个特性是40M频宽，该频宽是通过以前的两个20M信道叠加起来后生成的，并且叠加时两信道一个是主信道一个是副信道，这里的plus和minus都是针对主信道说的，所以11na_ht40plus代表40M频宽时的2个信道叠加向上加的叠加，例如当前信道是149，配成40M频宽需要叠加另外一个信道，就是149+153两个信道组成的40MHz频宽，11na_ht40minus代表信道叠加时是向下减的叠加，例如配了这个，信道161，就等于是161+157组成了40M频宽的新信道。
 802.11g也如a是一样的意思，只不过。由于802.11g只有1、6、11这3个信道，所以使用40M频宽的信道时只剩下了一个不重叠信道，所以在使用802.11ng时，不建议使用40MHz的频宽，使用默认的20MHz频宽即可。  
``` 

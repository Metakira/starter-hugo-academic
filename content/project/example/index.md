---
slides: example
url_pdf: ""
summary: A track I made using the expr~ component in PD, and an explanation.
url_video: ""
date: 2016-04-27T00:00:00.000Z
external_link: ""
url_slides: ""
title: Bytebeat music in Puredata!
tags:
  - Music
categories:
  - personal
links:
  - icon: youtube
    icon_pack: fab
    name: "Watch "
    url: https://youtu.be/AcS_Lmf_Nks?si=0am7-oLPkBadC2w_
image:
  caption: ""
  focal_point: Smart
  filename: featured.png
url_code: ""
---
Byte beats are basically "happy accidents" and can be considered the lowest form of generative music. The basic Idea of a bytebeat is that you apply mathematical functions onto signal waveforms, and that will somehow generate music. 

In this particular case *t* is an 8000hz timer that counts up. For example:

```
sin(t) * 127 + 127
```



You can choose traditional bytebeat where the output of your function is expected to be 0 to 255 or you can choose floatbeat where the output is expected to be -1 to +1.

No one really expected Bytebeats to be a possibility, and they were originally found as accidents in the early demoscenes. According to Viznut, the guy who first found out about the existence of bytebeats, there's a degree of *magic* afforded y the existence of Bytebeats.

I made mine after watching Gabriel Vinazza shred on the expr~ component of PD. My PD explorations were completely unrelated by the way. Somehow, it ended up being an entire song instead of just a short example of livecoding!
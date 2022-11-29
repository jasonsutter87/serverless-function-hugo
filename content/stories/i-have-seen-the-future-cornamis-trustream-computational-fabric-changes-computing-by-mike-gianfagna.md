---
title: I Have Seen the Future – Cornami's TruStream Computational Fabric Changes
  Computing by Mike Gianfagna
description: Cornami’s TruStream Computational Fabric Changes Computing by Mike Gianfagna
slug: cornamis-trustream-computational-fabric-changes-computing-by-mike-gianfagna
mainImage: /images/uploads/i-have-seen-the-future-cornamis-trustream-computational-fabric-changes-computing-by-mike-gianfagna-featured.jpg
thumbImage: /images/uploads/i-have-seen-the-future-cornamis-trustream-computational-fabric-changes-computing-by-mike-gianfagna-thumb.jpg
alt: Conceptual image of a lock icon amidst a field of data.
tags:
  - Investment
priority: "0.5"
date: 2021-11-05T18:05:00.000Z
pagetype: article
---
Here is another installment regarding presentations at the Linley Fall Processor Conference. Every now and again, you see a presentation at an event like this that shakes you up.  Sometimes in a good way, sometimes not so much. I attended the Cornami presentation on its new TruStream computational fabric and I was definitely shaken up and in a good way. As I watched the presentation, I kept thinking that I was seeing the future. And that brough back memories of the 1964/1965 World's Fair in New York. I recall General Motors had a pavilion there who's tagline was "I Have Seen the Future". I did a little digging and found that they used the exact same tagline at the 1939 World's Fair, also in NY. Now that's long-range, consistent branding. Enough history. Back to how Cornami's TruStream computational fabric changes computing.

The presentation was delivered by Paul Master, CTO and co-founder of Cornami. Paul began by talking about post-Von-Neumann algorithms. These are algorithms that cannot be implemented with current computing architectures typically due to their computational complexity and memory access requirements.  Machine learning is like this, but the focus of Paul's talk was implementing fully homomorphic encryption. This algorithm is definitely a post-Von-Neumann candidate as it breaks current computing architectures. The Forbes article cited here talks about this barrier. Hang in there, this will all start to make sense in a moment.

## Valuable and Fragile Data

Paul then touched on the value of data in the connected, AI/ML-driven world. He pointed out that "data is the new oil" in the AI/ML economy. Vast amounts of data are uploaded to the cloud each minute. The processing of that data informs tremendous potential for new products and services. But how is all this value protected? Paul offered a laundry list of things to consider:

Can you guarantee that...

* The processor/network/support silicon has not been compromised with a hardware trojan?
* The PCB has not been compromised by the addition of some trojan hardware?
* The microcode on your machine/network has not been compromised?
* The firmware has not been compromised?
* The software compilers and the RTL synthesis tools have not been compromised?
* The operating system has not been compromised?
* The Apps have not been compromised?
* There are no [man-in-the middle attacks](https://us.norton.com/blog/wifi/what-is-a-man-in-the-middle-attack)?
* Your employees have not been compromised?
* The employees of every company your data touches have not been compromised?

Have a headache yet? I did. Sadly, the answer to all these questions is **NO**, and this is the very essence of the fragile, unprotected world we live in. There's plenty of work going on here and no shortage of ideas on how to secure the supply chain, data storage, the network, the cloud and so on. All these approaches take an "outside in" view. That is, protect the data with safeguards around anything that touches that data. What if there was another way? What if you could inherently protect the data itself? I'm sure encryption is coming to mind as a cure. The problem with traditional encryption is twofold. First, current encryption algorithms are threatened by things like quantum computing, an example of a post-Von-Neumann architecture. While this threat is not here today, it will be soon. Second, the fact that you need to decrypt the data to operate on it is here today.

Ready to give up? Not so fast. Paul explained that fully homomorphic encryption (FHE) makes it possible to analyze or manipulate encrypted data without revealing the data to anyone. DARPA has called FHE **the holy grail of cryptography**. By protecting the data at its source, you can elegantly solve the massive problem of securing everything the data touches. This is an "inside out" view of the problem and it can change the world. There's just one problem. FHE needs to run in real time to support the process of operating on encrypted data and, as mentioned, FHE breaks current Von-Neumann architectures.
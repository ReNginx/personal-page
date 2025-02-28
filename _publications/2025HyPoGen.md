---
title: "Optimization-Biased Hypernetworks for Generalizable Policy Generation"
collection: publications
category: conferences
permalink: /publication/2025HyPoGen
excerpt: 'Hanxiang Ren, Li Sun, Xulong Wang, Pei Zhou, Zewen Wu, Siyan Dong, Difan Zou, Youyi Zheng, Yanchao Yang'
date: 2025-01-01
venue: 'The Thirteenth International Conference on Learning Representations (ICLR)'
paperurl: 'https://openreview.net/forum?id=CJWMXqAnAy'
# citation: 'Hanxiang Ren, Li Sun, Xulong Wang, Pei Zhou, Zewen Wu, Siyan Dong, Difan Zou, Youyi Zheng, Yanchao Yang. (2025). &quot;Optimization-Biased Hypernetworks for Generalizable Policy Generation.&quot; <i>The Thirteenth International Conference on Learning Representations (ICLR)</i>.'
---

Policy learning through behavior cloning poses significant challenges, particularly when demonstration data is limited. In this work, we present HyPoGen, a novel optimization-biased hypernetwork for policy generation. The proposed hypernetwork learns to synthesize optimal policy parameters solely from task specifications – without accessing training data – by modeling policy generation as an approximation of the optimization process executed over a finite number of steps and assuming these specifications serve as a sufficient representation of the demonstration data. By incorporating structural designs that bias the hypernetwork towards optimization, we can improve its generalization capability while only training on source task demonstrations. During the feed-forward prediction pass, the hypernetwork effectively performs an optimization in the latent (compressed) policy space, which is then decoded into policy parameters for action prediction. Experimental results on locomotion and manipulation benchmarks show that HyPoGen significantly outperforms state-of-the-art methods in generating policies for unseen target tasks without any demonstrations, achieving higher success rates and underscoring the potential of optimization-biased hypernetworks in advancing generalizable policy generation. 

The full paper can be accessed at:
[Optimization-Biased Hypernetworks for Generalizable Policy Generation](https://openreview.net/forum?id=CJWMXqAnAy)
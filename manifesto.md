---
layout: page
title: "manifesto."
permalink: /manifesto/
---

**ProductionML is an initiative to level up data scientists, enabling them to understand all the technologies, components and integration points which they need to be aware of for running machine learning systems in production, at scale with the help of data engineers for automation of the various pipeline processes.**

![Data Actors Venn Diagram]({{ "/assets/venn-diagram.png" | absolute_url }})

Over the past few years, data science has rightfully been the most hyped career track. Numerous online courses, bootcamps and books have been published on the topic(s). Most recently fast.ai[^1] and Andrew Ng's Deep Learning Specialization[^2] on Coursera have received due attention.

Depite all the extremely hard work being put into expediting the spread of machine learning knowledge, we see companies (those who are not AMZN, GOOG, FB, MSFT or the likes) struggle with building a machine learning backed feature/product[^3].

At most companies, the machine learning lifecycle consists of data scientists developing models offline and handing it off to data engineers to _productionize_ them and integrate them with the rest of the (microservice) ecosystem, at times leveraging completely different implementation technology (language/compute framework), slowing down the entire process for the company.

The data engineers want to automate these engineering handoffs, deployments and integrations with the rest of the enterprise ecosystem. The data scientists want to have confidence on the model's ability, its effectiveness and performance at scale. Most importantly both data scientists and data engineers want to move up the machine learning maturity scale to adapt to changing environments of the problem:

![Machine Learning Spectrum]({{ "/assets/ml-spectrum.png" | absolute_url }})

Our objective is to work through production technologies such as (but not limited to) Apache Spark[^4], ModelDB[^5], MLeap[^6], Apache MXNet[^7] and untangle cutting edge research being done in the area by pioneers such as Rise Lab[^8], Google BRAIN Team[^9] and Stanford DAWN[^10] to reduce the time it takes data scientists take their models to production, at scale eventually being able to build pipelines where models are trained, deployed, tuned, selected in an online manner following best practices[^11] and being weary of _"The High-Interest Credit Card of Technical Debt"_[^12].

We aim to achieve this through bridge workshops (to help data scientists become abreast of good software engineering practices, cloud computing[^13] and tools like docker) and meetups (to discuss research paper, follow courses and host talks on various related topics).

<hr>
<div class="footnotes">Footnotes:</div>
[^1]: [fast.ai](http://www.fast.ai)
[^2]: [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)
[^3]: [a16z Podcast: AI, from 'Toy' Problems to Practical Application](https://soundcloud.com/a16z/optimization-ai-in-practice)
[^4]: [Apache Spark Project](https://spark.apache.org/)
[^5]: [MIT CSAIL ModelDB](https://mitdbg.github.io/modeldb/)
[^6]: [MLeap](http://mleap-docs.combust.ml/)
[^7]: [Apache MXNet](https://mxnet.apache.org/)
[^8]: [Rise Lab](https://rise.cs.berkeley.edu/)
[^9]: [Google BRAIN Research Team](https://research.google.com/teams/brain/)
[^10]: [Stanford DAWN](http://dawn.cs.stanford.edu/)
[^11]: [Rules for Machine Learning: Best Practices for ML Engineering](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)
[^12]: [Machine Learning: The High-Interest Credit Card of Technical Debt](https://research.google.com/pubs/pub43146.html)
[^13]: [Stanford-CS349D: Cloud Computing Technology](https://web.stanford.edu/class/cs349d/)
---
title: "Profiling IoT-based Botnet Traffic using DNS"
author: "Dwyer et al"
date: 2019-12-09T21:13:14-05:00
categories: ["conference paper"]
tags: []
---



👥 Owen P. Dwyer, Angelos K. Marnerides, Vasileios Giotsas, Troy Mursch

📕 GLOBECOM 2019

📄 [Full paper](http://www.research.lancs.ac.uk/portal/en/publications/profiling-iotbased-botnet-traffic-using-dns%28b0098859-7762-473f-8f76-e8fe7ab27ac8%29.html)  


Internet-wide security and resilience have traditionally been subject to large-scale DDoS attacks initiated by various types of botnets. Since the Mirai outbreak in 2016 myriads of Mirai-alike IoT-based botnets have emerged. Such botnets rely on Mirai’s base malware code and they infiltrate vulnerable IoT devices on an Internet-wide scale such as to instrument them to perform large-scale attacks such as DDoS. As recently shown, DDoS attacks triggered by Mirai-alike IoT-based botnets go far beyond traditional pre-2016 DDoS attacks since they have a much higher amplification and their propagation is far more aggressive. Thus, it is of crucial importance to tailor botnet detection schemes accordingly. This work provides a novel DNS-based profiling scheme over real datasets of Mirai-alike botnet activity captured on honeypots that are globally distributed. We firstly discuss features used in profiling botnets in the past and indicate how profiling IoT-based botnets in particular can be improved by leveraging DNS information out of a single DNS record. We further conduct an evaluation of our developed feature set over various Machine Learning (ML) classifiers and demonstrate the applicability of our scheme. Our resulted outputs indicate that the proposed feature set can significantly reduce botnet detection time whilst simultaneously maintaining high levels of accuracy of 99% on average under the random forest formulation.


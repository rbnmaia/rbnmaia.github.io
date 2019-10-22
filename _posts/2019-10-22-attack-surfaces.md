---
title: 101 Attack Surfaces
---

Recently I was asked about the following - "Which of the following is accomplished by reducing the attack surface within the network?", so I found interesting to share a few points regarding this subject.

In crumbs, we can define the "attack surface" as the sum total of resources exposed to exploit within your network. Defending the attack surface was a lot less complicated when a defined corporate “perimeter” existed, neatly separating a company’s assets from the outside world. This paradigm shifted into the cloud and software-defined networking.

The idea of a contained perimeter is completely obsolete for today's information era. We quickly as technology progresses moved into networks boarding a lot of IoT (Internet of Things) devices or even corporate users bringing their devices in (Bring Your Own Device), the combination of both significantly increased our attack surfaces.

Take the example of IoT, in my opinion these devices are a "ticking bomb", there are a few restraints when they are being developed and security is an example of what is ignored during the process. It reminds me the software time-to-market business model, where publishers prefer to release a bugged software to meet their schedule and patch it later, rather than have a crisp quality product. We moved at a fast pace to the era that any device connected to the internet can now be the target of a cyberattack.

Everyone likes numbers and for sure at least if my awareness wasn't enough let me share you Symantec’s 2019 Internet Security Threat Report, that takes a deep dive into insights from the world’s largest civilian global intelligence network, revealing:

> * Formjacking attacks skyrocketed, with an average of 4,800 websites compromised each month.
> * Ransomware shifted targets from consumers to enterprises, where infections rose 12 percent.
> * More than 70 million records stolen from poorly configured S3 buckets, a casualty of rapid cloud adoption.
> * Supply chains remained a soft target with attacks ballooning by 78 percent.
> * “Smart Speaker, get me a cyber attack” — IoT was a key entry point for targeted attacks; most IoT devices are vulnerable.
 

From a lot of other ways to decrease this surfaces, let me share some effecient ones:

1. Eliminate Complexity

One of the most impactful ways to reduce the attack surface is by eliminating unnecessary complexity, which can creep into the best of networks over time. Complexity is often the result of poor policy management or incomplete information during rule creation, which can lead to:

 * Technical policy mistakes (e.g., duplicate or redundant rules)
 * Unused rules that have become stagnant and no longer serve a valid purpose
 * Overly permissive rule definitions that allow access well beyond what is necessary to meet business needs
 * Unnecessary complexity elevates the possibility of human error and risk, underscoring the importance of simplicity in security infrastructures and policy management.

 

2. Visualize Your Vulnerabilities

Vulnerability scanners give a severity score to a specific asset, application or host, but the score is incomplete without showing how an attacker could reach the weak spots. Visualizing vulnerabilities by creating a real-time model of what could happen in the context of network movement can provide this missing context. There are three methods that can greatly assist with this:

* Attack surface modeling – Creates a real-world model of the attack surface using: 
  1. network assets, or the prime targets for cybercriminals); 
  2. network topologies, which demonstrate the potential paths to a vulnerable asset; 
  3. policies, which dictate what access is permitted.
* Attack simulation – Reveals the ways attackers could traverse the network and exploit vulnerabilities.
* Patch simulation – Pairs with network policy to identify which patches could have the greatest impact on security (i.e., helps focus efforts on reducing the greatest amount of risk in the most efficient way possible).
 

3. Control Your Endpoints

The first step to reducing the impact of endpoints on the attack surface is gaining visibility into what’s happening on them. Independent process monitors keep all endpoints under constant surveillance and provide alerts when endpoint behaviors deviate from the norm. Monitoring network connections (to see how endpoints are relating to the network at-large) as well as user behavior (to quickly identify modified behavior on the endpoint) is also critical for timely threat detection and response.  

The second step is being able to control what the endpoints can actually do, and network policy is the most effective way to accomplish this. Policies draw a virtual perimeter around each endpoint to ensure that communication with the rest of the network conforms to security intent. When security drifts or when there’s abnormal endpoint behavior, adaptive policy kicks in to protect the network from any destructive spread.

 

4. Segment Your Network

You may already have perimeters around your network to protect the whole system, but segmenting your networks still makes a whole of sense, as it helps to reduce the attack surface by increasing the number of barriers an attacker encounters when attempting to travel through the network.

In a microsegmented world, we are able to drive security controls down to a single machine, partition, workload or application. Network segmentation not only helps to reduce the sum total of exploitable assets, but it also helps minimize dwell time (the time cybercriminals spend undetected on networks) by effectively putting “quick sand” in attackers’ paths to stop them in their tracks.

 

5. Prioritize Analytics

The final measure to reduce the attack surface is analysis. Security configuration assessments, traffic flow analysis and quantitative risk scores are three common methods of analysis that can be extremely effective in reducing the attack surface – and they’re methods you’re likely already using within your organization.

 

Building New “Perimeters”

While we cannot change the incentives and resources that give rise to cyberattacks, we can limit the opportunities available to cybercriminals. Following the five steps outlined above can help you create new network “perimeters” for today’s next-gen architectures designed to keep the bad guys on the outside looking in.

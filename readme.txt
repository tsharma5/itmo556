                                  CASE STUDY
"How Uber manages a million writes per second using Mesos and Cassandra across multiple Datacenters."

1.	What market does that company serve? (What do they do?) And have they always served that market?
Answer: Uber Technologies Inc. (doing business as Uber) is a ridesharing, taxi cab and transportation network company
headquartered in San Francisco, California in 785 metropolitan areas worldwide. I was founded in 2009 as UberCab by
Garrett Camp.

2.	What Operating System(s) are used?
Answer: Uber uses Apache Mesos distributed systems Kernel. (Based on principles as Linux Kernel abstracting CPU, memory,
storage away from machines enabling fault tolerant systems). Uber mobile app is available on Google play store for
Android devices and Apple store for iOS but not for Microsoft Windows, it can be booked from m.uber.com
(limited features).  Uber has a partnership with TomTom for navigation, maps and traffic data.

3. What programming languages/frameworks are used?
Answer:	Uber’s engineers primarily write in Python, Node.js, Go, and Java.

4.	What storage and what database technologies are used?
Answer:	Uber has it own database called Schemaless. Cassandra for high availability and low latency demands and Hadoop
warehouse for distributed storage and analytics for complex data.

5.	What is the current stock price and what was the IPO of the company? (if traded publicly.)
Answer:	Not traded publicly. Is worth $70 billion.

6.	What major obstacle (cost, system performance, QPS, etc, etc) was the company trying to overcome by implementing
this technology stack?
Answer: The biggest challenge that Uber faced was to store location data that was sent out in every 30 seconds.
Uber’s goal is for transportation to have 99.99% availability for everyone, everywhere so they decided to build their
own system by using two very capable open source components.

7.	What can you learn from this article relating to technology and infrastructure?
Answer:	We can learn about Distributed Systems Kernel, Mesos and Database, Cassandra. Mesos can run on 10s of thousands
of machines and is highly available. Cassandra has low latency rate, higher fault tolerance and is operationally simple.
Good integration with open source software such as Hadoop.

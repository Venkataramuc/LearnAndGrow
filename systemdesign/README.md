# Performance, Scalability, And High Availability: 3 Key Infrastructure Adaptability Requirements
=================================================================================================

Performance, scalability, and HA are often used interchangeably, and any confusion about them can result in unrealistic metrics and deployment delays. It is important to invest your time and understand the differences among these three approaches before you invest your money in resilient systems.

## Performance

Performance means system throughput under a given workload for a specific timeframe. Performance is validated by testing the scalability and the reliability of hardware, software and network. It is an ongoing process and not an end result. Performance requirements undergo massive changes as features and functionalities get added and eliminated to accommodate evolving business requirements.

## Scalability

Scalability simply refers to the ability of an application or a system to handle a huge volume of workload or expand in response to an increased demand for database access, processing, networking, or system resources.

## High Availability

High availability is when your apps remain available and accessible without any interruption and serve their intended function seamlessly. HA is achieved when your database cluster continues to operate, for example, even if one or more servers are blown up, shut down, or simply disengaged unexpectedly from the rest of the network.   

## Factors Affecting HA

Ensuring that apps hosted in the middle tier remain up and running requires database failover mechanism that directs queries to another server with a copy of the same data.  To deliver availability during a database failover you must ensure that:

The same components should be deployed to every instance in the cluster

Your failover mechanism should be aware of the availability of nodes in a given cluster along with their location

The failover mechanism should also track the progress of all the tasks so as to ensure a roll back when a given operation has failed

In case one of the servers in a cluster fails, database load balancing software in combination with a failover mechanism can ensure seamless rerouting of requests while preventing disruptions to the other users accessing the rest of the cluster.

Shifting the focus from Over Optimization to Scalability  

The most common mistake people make is over optimization– buying more infrastructure than they need. This approach is not only expensive, complicated and time-consuming, but it also needs top-notch engineering talent and expert consulting. In addition to increasing overall costs, it also wastes capital on non-revenue generating investments. Instead, shift your focus to scalability and shop for performance because if you invest in a high-end rack of servers it might cost you roughly $30,000 but if your DBAs and app developers have been working on your scalability plan for the past two months, the cost would be nothing less than $100,000. Be sure to calculate the cost of servers over their lifetime. So buy what you need today and wait to buy more until you must.

## Deploying Scalable Systems

Service level agreements determine the need for horizontal or vertical scaling. A stock trading system needs to scale instantly whereas an eCommerce app needs to scale only during big sale seasons when the traffic spikes. Database load balancing can help maximize throughput and minimize response times by distributing queries across multiple database servers.

Achieving High Availability with Database Load Balancing

Deploying database load balancing software is the best way to architect infrastructures for maximum resiliency in a manner that meets your business continuity needs.

Database load balancing software sits transparently between the applications and your database servers to ensure instant routing of traffic without needing application modifications. With database load balancing software, it is possible to scale out transparently and scale up instantly. It assures data recovery following a disaster, business continuity even with a high volume of traffic, reduced troubleshooting time with real-time root cause identification, and automatic failover without experiencing disruption or downtime. With advanced database load balancing features it empowers a server cluster to achieve high scalability, high performance and high availability at the same time. So, if you are not load balancing your database traffic, you end up spending a lot of time building efficiencies your enterprise will never put to use. Why put a Porsche engine on your skateboard if all you require is a skateboard?


# Difference between stream processing and message processing
================================================================
What is the basic difference between stream processing and traditional message processing? As people say that kafka is good choice for stream processing but essentially kafka is a messaging framework similar to ActivMQ, RabbitMQ etc

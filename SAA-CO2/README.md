# AWS SAA-C02 Study Guide


Table of Contents
==
1. <a href="#elastic-compute-cloud-ec2">Elastic Compute Cloud (EC2))</a>
2. <a href="#elastic-load-balancers-elb">Elastic Load Balancers (ELB)</a>


Elastic Compute Cloud (EC2)
==
Elastic Compute Cloud is

## Elastic Block Store (EBS)
---
An Amazon EBS volume is a durable, block-level storage device that you can attach to your instances. After you attach a volume to an instance, you can use it as you would use a physical hard drive.

* There are five types of EBS storage:
    * General Purpose SSD (gp2, and gp3)
    * Provisioned IOPS SSD, built for  (io1, io2, and io2 block express)
    * Throughput Optimized HDD (st1)
    * Cold HDD (sc1)
    * Magnetic (standard).

<table>
    <tr>
        <th>Class</th>
        <th>Type</th>
        <th>Max IOPS per volume</th>
        <th>Max throughput per volume</th>
        <th>Multi-attach</th>
        <th>Boot volume</th>
    </tr>
    <tr>
        <td rowspan=2>General Purpose SSD</td>
        <td>gp3</td>
        <td rowspan=2>16,000 (16 KiB I/O)</td>
        <td>1,000 MiB/s</td>
        <td rowspan=2>Not supported</td>
        <td rowspan=2>Supported</td>
    </tr>
    <tr>
        <td>gp2</td>
        <td>250 MiB/s</td>
    </tr>
    <tr>
        <td rowspan=3>Provisioned IOPS SSD</td>
        <td>io2 Block Express</td>
        <td>256,000 (16 KiB I/O)</td>
        <td>4,000 MiB/s	</td>
        <td rowspan=3>Supported</td>
        <td rowspan=3>Supported</td>
    </tr>
    <tr>
        <td>io2</td>
        <td rowspan=2>64,000 (16 KiB I/O) †</td>
        <td rowspan=2>1,000 MiB/s †</td>
    </tr>
    <tr>
        <td>io1</td>
    </tr>
    <tr>
        <td>Throughput Optimized HDD</td>
        <td>st1</td>
        <td>500 (1 MiB I/O)</td>
        <td>500 MiB/s</td>
        <td>Not supported</td>
        <td>Not supported</td>
    </tr>
    <tr>
        <td>Cold HDD</td>
        <td>sc1</td>
        <td>250 (1 MiB I/O)</td>
        <td>250 MiB/s</td>
        <td>Not supported</td>
        <td>Not supported</td>
    </tr>
    <tr>
        <td>Magnetic (Previous Generation)</td>
        <td>standard</td>
        <td>40–200</td>
        <td>40–90 MiB/s</td>
        <td>Not supported</td>
        <td>Supported</td>
    </tr>
</table>
† Maximum IOPS and throughput are guaranteed only on Instances built on the Nitro System provisioned with more than 32,000 IOPS



Elastic Load Balancers (ELB)
==
Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets and virtual appliances. Targets can be in one or more Availability Zones (AZs).



Amazon Cognito
==
The two main components of Amazon Cognito are user pools and identity pools.

User Pools
---


Identity Pools
---


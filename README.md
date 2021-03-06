aws-ping-traces
===============

This repository contains a compressed set of logs representing a
week's worth of ping times on Amazon AWS between:

* `us-east-1`, `us-west-1`, `us-west-2`, `eu-west-1`, `sa-east-1`, `ap-northeast-1`, `ap-southeast-1`
* `us-east-1b`, `us-east-1c`, `us-east-1d`
* Three hosts in `us-east-1b`

All servers were `m1.small` instances.

For more information, please see [my blog post](http://bailis.org/blog/communication-costs-in-real-world-networks/) or [contact me](http://www.bailis.org/contact.html).

**If you wish to use these traces in an academic publication, please reference [Highly Available Transactions: Virtues and Limitations](http://www.bailis.org/papers/hat-vldb2014.pdf) ([bib](http://www.bailis.org/papers/hat-vldb2014.bib)), to appear in VLDB 2014.**

Note that, according to [this paper](http://conferences.sigcomm.org/imc/2013/papers/imc125s-pelsserA.pdf), ping may overstate RTT variance.

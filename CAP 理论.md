refer [An illustrated proof of the CAP theorem](https://mwhittaker.github.io/blog/an_illustrated_proof_of_the_cap_theorem/)

## 1. 分布式系统的三个指标
- [1] 一致性Consistency
- [2] 可用性Availability
- [3] 分区容错 Partition tolerance

### 一致性 Consistency
写操作后的读操作，必须返回该值

### 可用性 Availability
只要收到用户的请求，服务器就必须给出回应。

### 分区容错 Partition tolerance
大多数分布式系统都分布在多个子网络中， 每个子网络就叫做一个分区 partition。区间通信可能失败
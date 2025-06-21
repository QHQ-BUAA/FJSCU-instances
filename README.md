# FJS and FJSCU Instances

This repository contains instances for the Heterogeneous Flexible Job-shop Scheduling (HFJS) and Heterogeneous Flexible Job-shop Scheduling with Cooperative Units (HFJSCU).

**Warning!** The data may not be entirely accurate. If you find any errors, please submit an issue. Always refer to the original papers for definitive information.

---

## FJS Instances

* **brandimarte**: 15 instances from [1]
* **dauzere**: 18 instances from [2]
* **behnke**: 60 instances from [3]

For more instances, please refer to: [Lei-Kun/FJSP-benchmarks](https://github.com/Lei-Kun/FJSP-benchmarks)

---

## FJSCU Instances

**Qu**: 30 instances

* `n`: number of jobs, with a range of (10, 50)
* `m`: number of machines, with a range of (5, 50)
* `cu`: number of collaborative units, with a range of (6, 40)
* `operation_range`: number of operations per job, with a range of ([2, 6], [3, 7])
* `time_range`: processing time range for operations, with a range of (30, 50)
* `machine_range`: number of optional machines per operation, with a range of ([2, 5], [20, 30])
* `cu_time_range`: working time range for collaborative units, with a range of (15, 30)

---

## References

1.  P. Brandimarte. Routing and Scheduling in a Flexible Job Shop by Tabu Search. Annals of Operations Research, 41(3):157–183, 1993.
2.  S. Dauzère-Pérès and J. Paulli. Solving the General Multiprocessor Job-Shop Scheduling Problem. Technical report, Rotterdam School of Management, Erasmus Universiteit Rotterdam, 1994.
3.  Behnke, D., & Geiger, M. J. (2012). Test instances for the flexible job shop scheduling problem with work centers. Arbeitspapier/Research Paper/Helmut-Schmidt-Universität, Lehrstuhl für Betriebswirtschaftslehre, insbes. Logistik-Management.

ab-graph
========

Bash script to benchmark some URLs with ab, and draw a graph of the results

I've used it on Ubuntu but should work on any Linux.

Assumes that you have installed:

* `ab` Apache Benchmark
* `gnuplot` graphing utility
* `display` image viewer


Usage: ./ab-graph -n <requests> -c <threads> URL1 [URL2] [URL3]..
  -c <threads> : number of threads (default 10)
  -n <requests> : number of requests (default 100)
  -h : this usage message



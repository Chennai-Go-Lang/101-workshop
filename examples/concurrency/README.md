# Overview

## Concurrency vs Parallelism

OS Overview

![OS Overview](assets/1-OS-process-and-its-threads.png)

> Image Credits: https://github.com/sathishvj/optimizing-go-programs#m-p-g

Concurrency vs Parallelism

![Concurrency vs Parallelism](assets/4-concurrency-and-parallelism.png)

> Image Credits: https://github.com/sathishvj/optimizing-go-programs#m-p-g

* Overview of Go scheduler

OS vs Go Scheduler

![OS vs Go Scheduler](assets/go-vs-os-scheduler.png)

> Image Credits: https://speakerdeck.com/kavya719/the-scheduler-saga?slide=15

OS Thread & Go Routine Scheduling

![Goroutine vs OS Thread](assets/os-thread-goroutine.png)
> Image Credits: https://speakerdeck.com/kavya719/the-scheduler-saga?slide=18

* `GOMAXPROCS` controls the max number of OS threads a go program can create

### Other Packages

* `context` package
  * Useful for signaling multiple goroutines at the same time
  * Useful for controlling goroutine execution
  * Useful for sharing values across goroutine boundaries

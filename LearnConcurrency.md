This page links to resources for learning about concurrency in Go.  The items are presented in order, from beginner material to advanced topics.

## Beginner
- Read [Effective Go: Concurrency](https://golang.org/doc/effective_go.html#concurrency)
- Study [The Go Programming Language Specification](https://golang.org/ref/spec), especially
    - [Go statements](https://golang.org/ref/spec#Go_statements)
    - [Channel types](https://golang.org/ref/spec#Channel_types)
    - [Send statements](https://golang.org/ref/spec#Send_statements)
    - [Receive operator](https://golang.org/ref/spec#Receive_operator)
    - [Select statements](https://golang.org/ref/spec#Select_statements)
- Code [A Tour of Go: Concurrency](http://tour.golang.org/concurrency/1)
- Read the [Frequently Asked Questions (FAQ)](http://golang.org/doc/faq), especially
    - [Why build concurrency on the ideas of CSP?](http://golang.org/doc/faq#csp)
    - [Why goroutines instead of threads?](http://golang.org/doc/faq#goroutines)
    - [Why are map operations not defined to be atomic?](http://golang.org/doc/faq#atomic_maps)
    - [What operations are atomic? What about mutexes?](http://golang.org/doc/faq#What_operations_are_atomic_What_about_mutexes)
    - [Why doesn't my multi-goroutine program use multiple CPUs?](http://golang.org/doc/faq#Why_no_multi_CPU)
    - [Why does using GOMAXPROCS > 1 sometimes make my program slower?](http://golang.org/doc/faq#Why_GOMAXPROCS)
    - [What happens with closures running as goroutines?](http://golang.org/doc/faq#closures_and_goroutines)
- Study [Go by Example](https://gobyexample.com) from [goroutines](https://gobyexample.com/goroutines) through [stateful goroutines](https://gobyexample.com/stateful-goroutines)

## Intermediate
- Watch [Go Concurrency Patterns](https://talks.golang.org/2012/concurrency.slide#1)
- Read [Share Memory By Communicating](http://blog.golang.org/share-memory-by-communicating) and do the [codewalk](http://golang.org/doc/codewalk/sharemem/)
- Read [Go Concurrency Patterns: Timing out, moving on](http://blog.golang.org/go-concurrency-patterns-timing-out-and)
- Watch [Concurrency is not Parallelism](http://talks.golang.org/2012/waza.slide#1)
- Read [Go Concurrency Patterns: Pipelines and Cancellation](http://blog.golang.org/pipelines)
- Study [Package sync](https://golang.org/pkg/sync/)
- Read [Introducing the Go Race Detector](http://blog.golang.org/race-detector)
- Watch [Go: code that grows with grace](http://talks.golang.org/2012/chat.slide#1)

## Advanced
- Watch [Advanced Go Concurrency Patterns](http://talks.golang.org/2013/advconc.slide#1)
- Read [Go Concurrency Patterns: Context](http://blog.golang.org/context)
- Study [The Go Memory Model](https://golang.org/ref/mem)
- Study [Package atomic](https://golang.org/pkg/sync/atomic/)
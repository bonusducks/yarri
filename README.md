# yarri (Yet Another Rust Raft Implementation)

## Goals

The primary goal of this project is to provide a complete library implementation of the [Raft consensus algorithm](https://raftconsensus.github.io) in Rust, as described in the PhD dissertation [_Consensus: Bridging Theory and Practice_](https://github.com/ongardie/dissertation#readme) and implemented by many, many people. 

Why has it already been implemented so many times? Because it's a lot easier to understand than [Paxos](https://en.wikipedia.org/wiki/Paxos_(computer_science)), and [ZAB](https://zookeeper.apache.org) already has a perfectly good implementation.

If it's been implemented so many times, why do it again? Well, because I couldn't find an implementation in Rust. Eh, that's a bit disingenuous. There is [at least one other](https://github.com/Hoverbear/raft) being done. Honestly, I wanted to do it myself to get back into systems development and finally start doing some modern distributed systems development.


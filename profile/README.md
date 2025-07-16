# pod

pod is a stake-based programmable layer-1 blockchain, designed with optimal
latency from first principles.

Even though blockchain is the most convenient way to describe pod, pod neither
contains blocks nor forms a chain. pod stands for Partially Ordered Dataset: it
is a service that receives unordered transactions submitted into the mempool
and orders them into a log. This ordering is "partial" because it allows
transactions to wiggle around their positions in a predictable fashion. This is
what enables pod's exceptional performance and low latency.

Read more in our
[How it works] (https://pod.network/how-it-works)
page and the pod paper:
[_pod: An Optimal-Latency, Censorship-Free, and Accountable Generalized Consensus Layer_](https://arxiv.org/pdf/2501.14931)
on arxiv.

# contractsexperiments

Experiments with the golang generics proposal.

At time of writing I could not get the WIP CL in
https://go-review.googlesource.com/c/go/+/187317 to do anything interesting
even to its own examples.

Despite that, this repo contains code that attempts to utilize the generics
proposal to build a generic double-ended queue data structure which pools
allocations and in the steady state does not allocate any memory.

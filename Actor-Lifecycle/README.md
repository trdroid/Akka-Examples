# Actor Lifecycle

An *actor* is automatically started by Akka when it is created. 

**Started**: An *actor* stays in the *started* state until it is stopped.

**Terminated**: An *actor* transitions to a *terminated* state when it is stopped.

### Restarting an *actor*

An *actor* in *started* state can be *restarted* to reset its internal state. 
When an *actor* is *restarted*, it is replaced by a fresh *actor* instance.

An *actor* can be restarted as many times as necessary. 

### Events





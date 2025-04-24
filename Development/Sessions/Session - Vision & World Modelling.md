_22 Apr 2025_
## Vision
We tried to understand how the vision should be built.

Looked at CNNs for inspiration. But CNNs check their kernels with a sliding window, which is very inefficient. We could use associations instead. But it has it’s own challenges.

Discussed how the output of vision should look like and decided to base on how it will be used.
## World Modelling
World Modelling is the primary use for vision. We want the agent to act based on the world model, not sensory inputs. That’s because we can enrich world model with data from knowledge base.

Discussed coordinates in the world model and agreed (I think) that they are not needed and relative positioning in a graph should be enough and more general.
![[files/Screenshot 2025-04-23 at 11.32.59.png]]
On image above is a world model of maze from a rat brain. Taken from [this video](https://www.youtube.com/watch?v=ceFFEmkxTLg).
## Identity Problem
We talked a lot about identity problem. How do we understand that the two objects at different time steps is the same object or different ones.

Vision can give us features that we will use to answer that question, but it’s not expected that all features will match. Also some features are not important for matching and some are required. 

Maybe that’s a higher-level reasoning thing, let’s leave it for now.
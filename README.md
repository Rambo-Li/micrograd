
# micrograd

This is a project forked from karpathy/micrograd. The structure is:

1. Engine: A data class that implements operations for forward pass, and functions for backward pass. This _backword function is defined while generating
   forward pass result and set in the result's method. When do backward pass, topo sort all the nodes and call backward() method on them. 

2. Neural Net: Define neuron, layer, mlp based the data class in the engine. Demo includes a SVM training.

3. Test: Compare computation result with pytorch.

4. Observability: Drawdot() for visualization, implemented in the trace_graph.ipynb.


### License

MIT

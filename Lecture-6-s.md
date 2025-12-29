
# 3.3 - Noted for Deep Learning For Graph

## GNN is two step process

1. Determine Node Computation Graph
2. Propagate and Transform Information

## Aggregate Neighbours
1. Generate node embeddings based on local neighbourhoods
2. Node aggregates information from neighbours using neural network
3. Every node gets to define its own Neural network architecture or computation graph based on the structure of the network around it.

## Deep Model
1. Models can be of arbitrary depth
2. At layer Zero - Embeddings would be simply its own input feature vectors
3. At layer K - Embeddings gets the information from the nodes that are k hops away

## Neighbourhood Aggregation
1. The Key difference between different Graph Nueral network architectures is how the different approaches aggregate the information across layers
2. Neighbourhood Aggregation function has to be order invariant

## Aggregation Functions 
1. Average or summation -
2. Deep Encoder - 

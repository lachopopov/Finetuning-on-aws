Recommended final AWS architecture(added by LP):

Client-->ALB--->ECS
The architecture is recommended due to huge delay incurred during the RAG work.

We need an async approach.
ALB-automatic load balancer
ECS-elastic container services.

The old one containing API GW->Lambda is not suitable


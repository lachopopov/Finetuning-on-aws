Recommended final AWS architecture:

Client-->ALB--->ECS
The architecture is recommended due to huge delay incurred during the RAG work.

We need an async approach.
ALB-automatic load balancer
ECS-elastic container services.

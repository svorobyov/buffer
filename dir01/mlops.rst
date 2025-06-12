MLOps
=====

Kubeflow
--------

1. Aris wants to avoid a vendor lock, and has a no go for data and
   models in a cloud.

2. `Kubeflow` is one of the most well-known open-source MLOps tool.

3. But it subsumes running and maintaining a Kubernetes cluster.

4. Do we have one? Do we want it? (I do not, it requires full-time
   attention for upgrades, security, troubleshooting.

5. AWS EKS is easier that on-prem Kubernetes, but probably we
   do not want AWS (it implies data and models on AWS)


MLFlow
------

1. `MLFlow` is another prominent MLOps open-source tool.

2. It can be easily deployed on-prem in a Docker container.

3. Low maintenance effort.

4. It is less powerful and has more restricted scope (compared to Kubeflow),
   concentrates on experimentation, optimization, tracing of models'
   hyperparameters.

5. `MLFlow` seems to be needed anyway, as long as model training is involved.



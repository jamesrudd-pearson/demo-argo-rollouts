# Demo Argo Rollouts

### Demos

1. basic-rollout - simple canary rollout that shifts weight between new and old revision
2. bluegreen-rollout - simple blue-green rollout that spins up new revision and activates "passive" service to route traffic that way. 
Easy and quick rollback if necessary.
3. istio-rollout - leverage istio virtual services to weight traffic percentages between new and old revision


https://argoproj.github.io/argo-rollouts/getting-started/#getting-started

https://argo-rollouts.readthedocs.io/en/release-1.5/features/bluegreen/

https://argo-rollouts.readthedocs.io/en/release-1.5/getting-started/istio/

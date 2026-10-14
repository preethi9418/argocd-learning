# argocd-learning
GitOps repo for my local kind cluster. ArgoCD watches `apps/`.
- apps/nginx    -> namespace `naa`
- apps/postgres -> namespace `default` (Secret `postgres-secret` is created manually, NOT in git)

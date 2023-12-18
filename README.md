# Multi-Cluster Management with ACM

## ManagedClusterSet

ManagedClusterSet은 

## GitOps 권한 (need to revisit)
```bash
oc adm policy add-cluster-role-to-user openshift-gitops-policy-admin system:serviceaccount:openshift-gitops:openshift-gitops-argocd-application-controller
```

#References
Policy Collection Github
- https://github.com/redhat-cop/acm-policies/blob/development/policies/policy-olm-disable-defaults/base/pl-olm-disable-defaults.yaml
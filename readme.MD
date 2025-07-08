# Ingress Controller
```
REGION_CODE=us-east-1
CLUSTER_NAME=naveenrajoli
ACC_ID=315069654700
```

### Permissions

* OIDC provider   # its used to access external resources or services from K8 to AWS
```
eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve
```
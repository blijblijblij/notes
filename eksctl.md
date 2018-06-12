# notes on eksctl

## create a new EKS cluster on aws

```bash
eksctl create cluster \
--cluster-name CLUSTER_NAME \
--nodes-min 1 \
--nodes-max 3 \
--region us-west-2 \
--node-type m5.xlarge
```

# Deploy acm resources through ACM

```
cd rhacm-demo
```

```
oc apply -k app-lifecycle/acm-resources/
```

All the resources will be created on the Hub cluster, after that the etherpad app will be deployed
to the clusters affected by the placement rule

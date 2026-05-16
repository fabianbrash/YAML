```MIG```


#### Example below of how to apply to your cluster

````

helm upgrade --install gpu-operator nvidia/gpu-operator \
  -f values-mig-base.yaml \
  -f values-mig-a100.yaml  # swap for your GPU generation
````

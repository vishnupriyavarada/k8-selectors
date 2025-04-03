## Selectors

taint node

```
kubectl taint nodes node1 key1=value1:NoSchedule

for ex: kubectl taint nodes node1 hardware=gpu:NoSchedule
gpu -> graphical processing unit. Mainly used for heavy computation like AI and ML work loads to run

kubectl taint nodes ip-192-168-47-131.ec2.internal  hardware=gpu:NoSchedule
```
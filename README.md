```
kubectl apply -f store.yaml
kubectl apply -f pv.yaml
helm upgrade --install minecraft -f values.yaml --set minecraftServer.eula=true,rcon.password=SET_ME .
```
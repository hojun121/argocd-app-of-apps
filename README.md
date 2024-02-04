# argocd-demo

DevOps 역량 강화를 위한 App-of-Apps 패턴 연습 레포입니다.



##### single application crd demo

```
kubectl apply -f single-application.yaml
```

##### app of apps patterns demo

![image](https://github.com/hojun121/argocd-app-of-apps/assets/107022839/dbb6b633-0742-4a54-a865-b38b096ebfc7)

```
kubectl apply -f app-of-apps.yaml
```

##### application set crd demo

```
kubectl apply -f application-set.yaml
```

##### multiple sources for applications
Required: argocd v2.6.0

```
kubectl apply -f multi-repo-application.yaml
```

##### argo-rollouts demo

```
kubectl apply -f argo-rollouts.yaml
```

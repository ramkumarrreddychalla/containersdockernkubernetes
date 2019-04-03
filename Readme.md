DOCKER         EQUAL COMMANDS TO       KUBERNETES
ENTRYPOINT                             COMMAND

CMD                                    ARGS


loaner12scl-2:dockerexamples Move Guest$ kubectl create -f pod-nginx-definitions.yml
pod "myapp-pod" created
loaner12scl-2:dockerexamples Move Guest$ kubectl create -f service-definition.yml 
service "myapp-service" created
loaner12scl-2:dockerexamples Move Guest$ kubectl get services
NAME            TYPE        CLUSTER-IP     EXTERNAL-IP   PORT(S)        AGE
kubernetes      ClusterIP   10.96.0.1      <none>        443/TCP        7h
myapp-service   NodePort    10.97.112.71   <none>        80:30008/TCP   13s
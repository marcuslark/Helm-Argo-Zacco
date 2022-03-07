Create new project

`oc new-project ctfd`

Install:

`helm upgrade --install ctfd ctfd`

other stuff:

`helm delete multi-juicer`

`oc delete project multi-juicer`

`oc status`

`kubectl get all`

List IP and ports: 
`kubectl --namespace ctfd get services -o wide`

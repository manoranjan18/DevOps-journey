Kubernetes architecture -Deep dive 
---------------------------------------------------------------
In previous post you must have understood what is kubernetes and its introduction 
Now we're gonna look deep into kubernetes 

the kube architecture has two main thing one is master node and another one is worker node .According to me it is community and 
friends 

Kube ctl is the command line tool that is used to interact with the kubernetes 

master/Community node 
--------------------------------------------------------------------

In community /master node there is three main important things that is 

1.API Server 

2.Scheduler

3.controller Manager 

API Server is the brain of the kubernetes via the api server only master node can able to 
do the things that the user wants to be done

scheduler is the one which will schedules what should be done first and what should be done afer 

controller manager is the one which manages many controller which are present in the master node 

ETCD

It is a database kind of thing that will  record whatever happens in the whole master and worker node
 
Worker /friends node
------------------------------------------------------------ 

In Worker /friends node there are many important things 

1.kubelet

2.kube -proxy

3.Container runtime

4.pod 

Kubelet always asks the api server whwther an pod was assignes to me or not 

Kube -proxy ensure that it has a stable connection to internet 

container runtime contains  pod and it is responsible for the runnning of the containers 

pod is the one which has container inside it ...you can have single container or multiple container 
 

  


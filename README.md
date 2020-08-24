# CKAD-Prepration
. create a deployment  with the following spec:
- use the image xxxxxxx .
- image should be tag 4.
- label the deployment xxxxxx. 
2. create a pod with following spec.
- the pod should mount a volume under /opt/xxxxx
- the persistent volume claim should use a physical volume which last for the lifetime of the pod.
3. There is a pod with an errored container.
- find the pod with error
- troubleshoot the error and make sure the container in the pod is up and running.
4. create a pod which requests 300Mi cpu and is placed on node01. 
5. Expose the deployment webapp in namespace exam
- the deployment shold be accessible within the cluster.
- the application should run on port 8080.
6. identify the pod with high cpu utilization and redirect the output to a file. the file format should be "namespace/pod".
7. there is a problem in a pod. identify the pod and redirect the pod related error events to a file in /opt/..... # you have to use events and name of the container within pod. 
8. a deployment had issues, troubleshoot to bring all pods into READY state.
9. create a deployment from nginx image. upgrade the deployment to nginx version 1.17. rollback the deployment.
10. Create a pod with following specs.
- it should mount a secret under /etc/super-secret
- it should setup environment varialbe ENVIRONMENT with the value of the configmap my-config.
- create my-config configmap with specs var1/val2.
- create the needed secret with the specs given in file /opt/xxxxxx 
11. Create a pod with a main container and a sidecar container with following specs.
- main container should run the image xxxxxxx.
- main container should run the command "some long command with loop to generate logs"
- sidecar container should run the image xxxxxx.
- sidecar container should mount a configmap with given spec under file /opt/xxxxx. 
- sidecar container should be able to read the logs from main container and process it.
12. Taint node01 with given key,value,effect. Create a pod with following specs.
- pod should mount a given pvc under /etc/xxxxx
- pod should be scheduled on node01.
13. A given deployment is running deployment/xyz. Store the deployment details in json or yaml format in file /opt/CKAD0003/xxxxxx.
14. Create a namespace my-namespace. Deploy a pod in this namespace with capability to run system time as root.
15. cronjob with given specs. the job should exit if not completed within 20 seconds.
16. there are 2 pods, db and proxy. there is a third pod webapp. you have to allow traffic to proxy and db pods only from webapp pod. All network policies are in place and do not delete/modify
any netowrk policies to achieve the desired result.
17. create a job with following specs:
- job should use the image "some custom image"
- it should terminate if not executed within 60 seconds.
18. There is a deployment running. update the deployment with following spec:
- change replica set to 3.
- run the deployment as service account "some SA"
- create the SA if not exists.
19. create a pod with following specs:
- label it as xxxxx # 2 labels.
- set environment varialbe as "some env variable"

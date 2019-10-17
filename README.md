# AICoE Hackfest (XJKLS)

## step 1:- go to github.com/sub-mod/rhte-hackfest/   
## step 2:- access tekton dashboard and openshift cluster
  
---
### Login to Openshift cluster
```
oc login https://api.cluster-rhtegpu-0e4c.rhtegpu-0e4c.open.redhat.com:6443 
username: user1  
password:  
namespace: tekton-demo  
sa:  tekton-demo  
```

```
'oc' client: https://api.cluster-rhtegpu-0e4c.rhtegpu-0e4c.open.redhat.com:6443   
user name : 'opentlc-mgr'   

oc create sa <abc>
oc adm policy add-scc-to-user privileged -z <abc> -n <NS>  
oc adm policy add-role-to-user edit -z <abc> -n <NS> 
```
### Openshift Master Console: 
http://console-openshift-console.apps.cluster-rhtegpu-0e4c.rhtegpu-0e4c.open.redhat.com  
  
### Tekton-Dashboard  
http://tekton-tekton-pipelines.apps.cluster-rhtegpu-0e4c.rhtegpu-0e4c.open.redhat.com/#/pipelines  

### Tensorflow Project:  
https://github.com/sub-mod/tf-mnist  
  
### Some project Ideas
Project 1: Build a ML workflow using tektonCD on Openshift 4 with tf-mnist project.  
Project 2: Build a simple golang based operator using operator-sdk for ML workflow using buildconfig on Openshift 4 with  tf-mnist project.   

---
  
### Download oc client from  
https://mirror.openshift.com/pub/openshift-v4/clients/ocp/4.1.14/openshift-client-linux-4.1.14.tar.gz  
  
### Tekton examples    
https://gist.github.com/sub-mod/45baf9a187bd64b48dcb738867239d17   
https://github.com/tektoncd/catalog  
https://github.com/openshift/pipelines-catalog  
https://github.com/sub-mod/openshift-pipelines-examples  
https://github.com/sub-mod/tf-tekton  
https://github.com/sub-mod/tf-mnist/tree/master/tekton   
  
### S2I workflow for Tensorflow Applications  
https://mojo.redhat.com/groups/red-hat-artificial-intelligence-center-of-excellence-ai-coe/projects/thoth/blog/2019/09/12/s2i-workflows-for-tensorflow-applications

# EVT Helm Chart for Hashicorp Consul

_Note: This document needs to be completed_


## Jenkins Server Url 


https://jenkins.evtcorp.lab/


## Persistance Volume Claim

Created a PVC form outside the chart and using that volume claim for the jenkins deployment

Please find the file under the 

https://bitbucket.org/evtco/evt-helm-charts/src/master/evt-jenkins/



## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm install --name my-release -f values.yaml stable/jenkins
```


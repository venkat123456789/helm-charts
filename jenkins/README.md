# EVT Helm Chart for Hashicorp Consul

_Note: This document needs to be completed_


## Jenkins Server Url 


https://jenkins.org.lab/


## Persistance Volume Claim

Created a PVC form outside the chart and using that volume claim for the jenkins deployment




## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm install --name my-release -f values.yaml stable/jenkins
```


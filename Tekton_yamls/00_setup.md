# Project setup

Create a namespace

```
oc new-project motd-tekton
```

Create a secret

```
oc create secret docker-registry regcred --docker-server=https://index.docker.io/v1/ --docker-username=<username> --docker-password=<password> --docker-email=<your email> -n motd-tekton
```


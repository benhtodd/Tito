# ***ALL HAIL THE MEOC!!***

Converted to run on vSphere 7 with Tanzu as well as add config maps, secrets amd other kubernetes components as separate yaml files wrather one big file, for learning purposes.

We will create 6 yaml files

1. Secrets to hold an encrypted password variable that will be passed the titoDB in the tito-sql container
2. Config Map to hold environment vaiables to be passed to the deployments
3. Deployment/Pod for tito-fe
4. External Service for tito-fe
5. Deployment/Pod for tito-sql
6. Service for tito-sql
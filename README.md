# flask-helm-chart
A basic example of a helm chart that deploys a flask-app with a database.

The flask app code an be found here: https://github.com/jalzreibi/flask-app


To add the helm chart repository, please run the command:
`helm repo add [repo-name] https://jalzreibi.github.io/flask-helm-chart/`

to install the helm chart, please run the command:
`helm install [helm-release-name] [repo-name]/flask-helm-chart`



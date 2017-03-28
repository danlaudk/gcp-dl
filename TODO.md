## TODO

- Deploy a docker container on this machine. Currently, we have a `docker build -t "gcr.io/<project_name>/<repo_name>"` to deploy this to the repository followed by a `gcloud docker -- push gcr.io/<project_name>/<repo_name>`. Now we need to run this on the machine.


docker-machine create --driver google \
--google-project creator-ml \
--google-zone us-east1-d \
--google-use-existing dockertester
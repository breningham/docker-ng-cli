# docker-ng-cli

Docker container for Angular CLI

Example usage
```
docker run -u $(id -u) --rm -v "$PWD":/app trion/ng-cli ng new MyDemo
cd MyDemo
docker run -u $(id -u) --rm -v "$PWD":/app trion/ng-cli ng serve -host 0.0.0.0
docker run -u $(id -u) --rm -v "$PWD":/app trion/ng-cli ng build
```
To run Angular CLI unit tests in docker see docker-ng-cli-karma and docker-ng-cli-e2e projects and respective trion/ng-cli-karma and trion/ng-cli-e2e docker iamges.
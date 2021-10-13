#First show KubeLinter documentation

https://github.com/stackrox/kube-linter

# Show CLI options

kube-linter --help

# Show that lints are able to be done through vscode

1. Lint all manifests and showcase all control failures.

kube-linter lint manifests

2. Lint specific yaml files

kube-linter lint manifests/carts-db

3. Use a configfile  and showcase the use of the configfile using kubelinter check

kube-linter lint manifests/carts-db --config configs/config_carts_db_permissive.yaml

4. Show if I wanted to use the strict lint 

kube-linter lint manifests/carts-db --config configs/config_carts_db_strict.yaml

4. Show github action




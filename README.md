### Useful now.sh commands

- now: deploy project
- now alias: aliases project
- now ls: list all projects
- now rm <PROJECT>: remove project
- now rm <PROJECT> --safe: remove remove deployments for that projects that are not aliased
- now secret add <NAME> <VALUE>: add secrets to now project
- @<SECRET>: use a secret in project
- now secret rename: rename a secret
- now secret rm: remove a secret
- now secret help: help with secrets
- now -e <NAME>="<VALUE>": set up run time env variables
- now --build-env NODE_ENV=production: set up build time env variables

https://zeit.co/docs/features/build-env-and-secrets

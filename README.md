This is a super basic buildpack to run node.js applications in Cloud Foundry.



My goals here are minimalism. This buildpack only installs the node binary into the droplet/container and sets up the start command.


I'd exepect this to be the last step of a multi buildpack pipeline, there is a counterpart to run `npm i && npm run build` that can be used first.


Here are some settings and their defaults:

| nodejs-version  | 14.0          |
| npm-version     | 6.14.4        |
| entrypoint      | dist/index.js |
| | |




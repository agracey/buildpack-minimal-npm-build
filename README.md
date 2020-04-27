This is a super basic buildpack to build node.js applications in Cloud Foundry.



My goals here are minimalism. This buildpack only installs dependencies and runs the script specified in build
Here are some settings and their defaults:

| nodejs-version  | 14.0          |
| npm-version     | 6.14.4        |
| entrypoint      | dist/index.js |
| | |



